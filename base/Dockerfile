FROM ubuntu:18.04

LABEL mantainer="gvgramazio@gmail.com" \
      version="0.1"

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
  texlive-base \
  && apt-get clean
