# Go cross compiler (xgo): Go 1.15.12
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM suburbandad/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11512

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.15.12.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=bbdb935699e0b24d90e2451346da76121b2412d30930eabcd80907c230d098b7 && \
  \
  $BOOTSTRAP_PURE
