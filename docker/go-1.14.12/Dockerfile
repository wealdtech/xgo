# Go cross compiler (xgo): Go 1.14.12
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM suburbandad/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11412

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.14.12.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=fb26f951c88c0685d7df393611189c58e6eabd3c17bdaef37df11355ab8db9d3 && \
  \
  $BOOTSTRAP_PURE
