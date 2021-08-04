# Go cross compiler (xgo): Go 1.15.13
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM suburbandad/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11513

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.15.13.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=3d3beec5fc66659018e09f40abb7274b10794229ba7c1e8bdb7d8ca77b656a13 && \
  \
  $BOOTSTRAP_PURE
