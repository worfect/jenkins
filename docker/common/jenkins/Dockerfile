FROM jenkinsci/blueocean:1.24.7
#https://gitlab.alpinelinux.org/alpine/aports/-/issues/12396

USER root

RUN apk add --no-cache openssl-dev gcc libc-dev rust cargo make gettext docker-compose

USER jenkins