FROM jupyter/datascience-notebook

USER root
RUN apt-get update -qq && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends wget zsh vim && \
    rm -rf /var/lib/apt/lists/* /var/cache/apt
USER jovyan
