# nginx-php-fpm-loadbalance

```mermaid
  graph TD;
      Proxy-->Site1;
      Proxy-->Site2;
      Proxy-->Site3;
      Site1-->php-fpm1;
      Site1-->php-fpm2;
      Site1-->php-fpm3;
      php-fpm1-->Site1;
      php-fpm2-->Site1;
      php-fpm3-->Site1;
      Site2-->Php-fpm;
      Site3-->Php-fpm;
```

