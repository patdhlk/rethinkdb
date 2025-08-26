FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu24.04

# Install necessary packages using a single RUN command to optimize layers
RUN apt-get update
RUN apt-get install -y build-essential protobuf-compiler \
    python3 python-is-python3 \
    libprotobuf-dev libcurl4-openssl-dev \
    libncurses5-dev libjemalloc-dev wget m4 g++ libssl-dev


WORKDIR /workspace
USER vscode