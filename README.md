Generate make file:

Linux:
```
./auto/configure \
    --prefix= \
    --conf-path=conf/nginx.conf \
    --pid-path=logs/nginx.pid \
    --http-log-path=logs/access.log \
    --error-log-path=logs/error.log \
    --with-pcre=lib/pcre-8.44 \
    --with-zlib=lib/zlib-1.2.11 \
    --with-openssl=lib/openssl-OpenSSL_1_1_1i \
    --add-module=./nginx-http-flv-module
```

