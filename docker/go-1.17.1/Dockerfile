# Go cross compiler (xgo): Go 1.17.1
# Copyright (c) 2020 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM wealdtech/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11701

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.17.1.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=dab7d9c34361dc21ec237d584590d72500652e7c909bf082758fb63064fca0ef && \
  \
  $BOOTSTRAP_PURE
