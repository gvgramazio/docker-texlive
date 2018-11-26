FROM gvgramazio/texlive:base

LABEL mantainer="gvgramazio@gmail.com" \
      version="0.1"

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
  texlive-full \
  && apt-get clean
