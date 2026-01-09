# Base image
FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Install system dependencies
RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        build-essential \
        curl \
        git \
        ca-certificates \
        pkg-config \
        libssl-dev \
        && rm -rf /var/lib/apt/lists/*
