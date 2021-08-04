# Go cross compiler (xgo): Go 1.16.3
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11603

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.16.3.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=951a3c7c6ce4e56ad883f97d9db74d3d6d80d5fec77455c6ada6c1f7ac4776d2 && \
  \
  $BOOTSTRAP_PURE
