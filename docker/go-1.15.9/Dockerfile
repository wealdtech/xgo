# Go cross compiler (xgo): Go 1.15.9
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM suburbandad/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11509

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.15.9.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=a55f3e75bc1098045851d40ea74f9d77efc7958e9af85131a96ca387d38b1834 && \
  \
  $BOOTSTRAP_PURE
