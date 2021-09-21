# Go cross compiler (xgo): Go 1.16.7
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM wealdtech/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11607

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.16.7.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=7fe7a73f55ba3e2285da36f8b085e5c0159e9564ef5f63ee0ed6b818ade8ef04 && \
  \
  $BOOTSTRAP_PURE
