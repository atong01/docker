FROM buildpack-deps:xenial

MAINTAINER Alex Tong "alexanderytong@gmail.com"

RUN apt-get update && apt-get install -y --no-install-recommends \
        sudo \
    && rm -rf /var/llib/apt/lists/*

