FROM ubuntu:18.04
MAINTAINER ZeroneVu <zeronevu@gmail.com>

# gcc for cgo, and all other common packages
RUN apt update && apt install -y --no-install-recommends \
  curl \
  git \
  nano \
  && rm -rf /var/lib/apt/lists/*
