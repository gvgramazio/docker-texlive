FROM ubuntu:18.04

LABEL mantainer="gvgramazio@gmail.com" \
      version="0.1"

ARG DEBIAN_FRONTEND=noninteractive

# Install texlive-base
RUN apt-get update \
  && apt-get install -y --no-install-recommends \
    texlive-base=2017.20180305-1 \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

# Remove documentation packages of latex to save disk space
RUN apt-get remove -y "texlive-*-doc"
