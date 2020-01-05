FROM ubuntu:18.04
MAINTAINER ZeroneVu <zeronevu@gmail.com>

RUN apt update && apt install -y --no-install-recommends \
  ca-certificates \
  openssh-client \
  curl \
  wget \
  git \
  nano \
  && rm -rf /var/lib/apt/lists/*

WORKDIR /home