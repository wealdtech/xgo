# Go cross compiler (xgo): Go 1.15.5
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM suburbandad/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11505

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.15.5.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=9a58494e8da722c3aef248c9227b0e9c528c7318309827780f16220998180a0d && \
  \
  $BOOTSTRAP_PURE
