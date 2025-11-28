FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

# Install Ruby and Jekyll dependencies
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
    ruby-full \
    build-essential \
    zlib1g-dev \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
