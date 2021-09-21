# Go cross compiler (xgo): Go 1.16.8
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM wealdtech/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11608

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.16.8.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=f32501aeb8b7b723bc7215f6c373abb6981bbc7e1c7b44e9f07317e1a300dce2 && \
  \
  $BOOTSTRAP_PURE
