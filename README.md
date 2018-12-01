# docker-texlive

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/0b5c727fa3b64375b700a7c26e17adce)](https://app.codacy.com/app/gvgramazio/docker-texlive?utm_source=github.com&utm_medium=referral&utm_content=gvgramazio/docker-texlive&utm_campaign=Badge_Grade_Dashboard)

A very minimal image to compile your LaTeX files based on Ubuntu 18.04.

- `texlive:base` is the base image for all other images in this repository. It comes with Ubuntu 18.04 and `texlive-base`. This image is suggested only if you have very few needs or if you want to build a personalized version of texlive.
- `texlive:full` extend `texlive:base` with `texlive-full`. This is the suggested image.
- `texlive:experimental-base` is an experimental version of `texlive:base`. Use it at your own risk.
- `texlive:experimental-full` is an experimental version of `texlive:full`. Use it at your own risk.
- `texlive:latest` is an alias for `texlive:full` but in the future it could direct to other images. To avoid unexpected behavior in the future is better to use `texlive:full` instead.
