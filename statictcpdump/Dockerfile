FROM alpine:3 AS builder

RUN apk add --no-cache \
    build-base \
    libpcap-dev \
    linux-headers \
    bison \
    flex \
    git \
    autoconf \
    automake \
    libtool \
    bash

WORKDIR /src

COPY gen .

ENTRYPOINT ["/src/gen"]
