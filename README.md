# PHP/nginx deployment starter kit

## Contains:

- [nginx:alpine](https://hub.docker.com/_/nginx/)
- [php:fpm-alpine](https://hub.docker.com/_/php/)

## Usage:

By default on linux system all `*.sh` files should be executable. 
To start php/nginx container just type:

`./start.sh start`

To check that everything is ok check out 127.0.0.1:8081 you should see result of `<?php phpinfo();`