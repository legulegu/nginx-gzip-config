# nginx-gzip-config

```
server {
    gzip on;
    gzip_types      text/plain application/javascript application/x-javascript text/javascript text/xml text/css;
    gzip_proxied    no-cache no-store private expired auth;
    gzip_min_length 1000;
    ...
}
```
