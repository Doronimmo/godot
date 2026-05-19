FROM ghcr.io/monkeyx-net/portmaster-build-templates/portmaster-builder:aarch64-latest
USER root
RUN pip3 install --user scons && \
    echo "$HOME/.local/bin" >> $GITHUB_PATH
WORKDIR /workspace
