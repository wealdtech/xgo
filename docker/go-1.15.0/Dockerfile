# Go cross compiler (xgo): Go 1.15
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM suburbandad/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11500

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.15.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=2d75848ac606061efe52a8068d0e647b35ce487a15bb52272c427df485193602 && \
  \
  $BOOTSTRAP_PURE
