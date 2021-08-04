# Go cross compiler (xgo): Go 1.16.2
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11602

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.16.2.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=542e936b19542e62679766194364f45141fde55169db2d8d01046555ca9eb4b8 && \
  \
  $BOOTSTRAP_PURE
