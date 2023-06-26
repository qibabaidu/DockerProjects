FROM ubuntu:18.04

# Set env
ENV PYTHON_ROOT_PATH /usr/local/python-3.7.5
ENV PATH /usr/local/bin:/root/.local/bin:$PATH

# Install base tools
RUN apt update \
    && DEBIAN_FRONTEND=noninteractive apt install -y \
    vim \
    wget \
    curl \
    xz-utils \
    net-tools \
    openssh-client \
    git \
    ntpdate \
    tzdata \
    tcl \
    sudo \
    bash-completion