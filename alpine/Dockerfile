FROM alpine:3.12

ARG SCRAPY_VERSION=2.2.0

RUN set -eux \
    && apk add --no-cache \
        libxml2-dev \
        libxslt-dev \
        libffi-dev \
        openssl-dev \
        musl-dev \
        gcc \
        python3-dev \
        py-pip \
    && pip install scrapy==$SCRAPY_VERSION
