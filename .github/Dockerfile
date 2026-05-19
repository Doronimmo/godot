FROM ghcr.io/monkeyx-net/portmaster-build-templates/portmaster-builder:aarch64-latest
USER root
RUN apt-get update && \
    apt-get install -y --no-install-recommends python3-scons && \
    rm -rf /var/lib/apt/lists/*
WORKDIR /workspace
