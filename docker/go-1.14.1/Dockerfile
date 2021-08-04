# Go cross compiler (xgo): Go 1.14.1
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM suburbandad/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11401

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.14.1.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=2f49eb17ce8b48c680cdb166ffd7389702c0dec6effa090c324804a5cac8a7f8 && \
  \
  $BOOTSTRAP_PURE
