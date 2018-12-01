FROM ubuntu:18.04

LABEL mantainer="gvgramazio@gmail.com" \
      version="0.1"

ARG DEBIAN_FRONTEND=noninteractive

# Install texlive-base
RUN apt-get update --no-install-recommends \
  && apt-get install -y \
    texlive-base \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

# Remove documentation packages of latex to save disk space
RUN apt-get remove -y "texlive-*-doc"
