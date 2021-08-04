# Go cross compiler (xgo): Go 1.15.14
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM suburbandad/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11514

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.15.14.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=6f5410c113b803f437d7a1ee6f8f124100e536cc7361920f7e640fedf7add72d && \
  \
  $BOOTSTRAP_PURE
