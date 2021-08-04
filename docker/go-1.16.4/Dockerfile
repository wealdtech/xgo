# Go cross compiler (xgo): Go 1.16.4
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11604

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.16.4.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=7154e88f5a8047aad4b80ebace58a059e36e7e2e4eb3b383127a28c711b4ff59 && \
  \
  $BOOTSTRAP_PURE
