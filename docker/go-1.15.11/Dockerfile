# Go cross compiler (xgo): Go 1.15.11
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM suburbandad/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11511

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.15.11.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=8825b72d74b14e82b54ba3697813772eb94add3abf70f021b6bdebe193ed01ec && \
  \
  $BOOTSTRAP_PURE
