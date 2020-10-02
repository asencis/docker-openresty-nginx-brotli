# docker-openresty-nginx-brotli

*The simpliest solution to add brotli support to your nginx server*

This image is intended to work with [Valian/docker-nginx-auto-ssl](https://github.com/Valian/docker-nginx-auto-ssl), and is only possible thanks to [OpenResty](https://github.com/openresty/openresty) and [lua-resty-auto-ssl](https://github.com/GUI/lua-resty-auto-ssl).

It is built on the [docker-openresty/alpine/Dockerfile.fat](https://github.com/openresty/docker-openresty/blob/master/alpine/Dockerfile.fat) Docker Image, and inserts support for Google's Brotli compression nginx module [google/ngx_brotli](https://github.com/google/ngx_brotli).

**Image status**: used in production.

# Usage

```
FROM asencis/openresty-nginx-brotli
```
