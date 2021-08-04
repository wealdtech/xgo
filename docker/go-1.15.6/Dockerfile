# Go cross compiler (xgo): Go 1.15.6
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM suburbandad/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11506

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.15.6.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=3918e6cc85e7eaaa6f859f1bdbaac772e7a825b0eb423c63d3ae68b21f84b844 && \
  \
  $BOOTSTRAP_PURE
