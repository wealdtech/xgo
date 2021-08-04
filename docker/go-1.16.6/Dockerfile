# Go cross compiler (xgo): Go 1.16.6
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11606

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.16.6.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=be333ef18b3016e9d7cb7b1ff1fdb0cac800ca0be4cf2290fe613b3d069dfe0d && \
  \
  $BOOTSTRAP_PURE
