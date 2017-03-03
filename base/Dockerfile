# Reference: https://raw.githubusercontent.com/JAremko/alpine-vim/master/alpine-vim-base/Dockerfile
# Difference being: try to use buit package
FROM alpine:3.5

MAINTAINER Rohit Mohta <rmohta.coder@gmail.com>
# As of 02-March-2017, current version of vim is: vim-8.0.0349-r0
RUN apk --no-cache add vim \
# Cleanup
    && rm -rvf /var/cache/* \
    /var/log/* \
    /var/tmp/* \
    && mkdir /var/cache/apk


