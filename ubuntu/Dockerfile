FROM ubuntu:24.04

LABEL org.opencontainers.image.source=https://github.com/system4-tech/task-runner-images
LABEL org.opencontainers.image.description="Task Runner Ubuntu 24.04"
LABEL org.opencontainers.image.licenses=MIT

ENV DEBIAN_FRONTEND=noninteractive

RUN set -eux; \
    apt-get update; \
    apt-get install -y --no-install-recommends \
    binutils \
    build-essential \
    bzip2 \
    ca-certificates \
    coreutils \
    curl \
    dnsutils \
    dos2unix \
    findutils \
    git \
    golang-go \
    iputils-ping \
    jq \
    mediainfo \
    net-tools \
    nodejs \
    openssh-client \
    p7zip-full \
    p7zip-rar \
    parallel \
    pigz \
    postgresql-client \
    python3 \
    python3-pip \
    python3-setuptools \
    python3-dev \
    rsync \
    shellcheck \
    sqlite3 \
    tar \
    telnet \
    tree \
    tzdata \
    unzip \
    wget \
    yq \
    zip \
    ; rm -rf /var/lib/apt/lists/*
