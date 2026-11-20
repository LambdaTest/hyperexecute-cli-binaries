# Republishes the Docker Hub image on ghcr.io with OCI labels, so the package
# shows on this repository's page. The layers are unchanged; only labels are added.
ARG SOURCE_IMAGE
FROM ${SOURCE_IMAGE}
LABEL org.opencontainers.image.source="https://github.com/LambdaTest/hyperexecute-cli-binaries" \
      org.opencontainers.image.url="https://github.com/LambdaTest/hyperexecute-cli-binaries" \
      org.opencontainers.image.vendor="TestMu AI" \
      org.opencontainers.image.description="Official Docker image for the TestMu AI (formerly LambdaTest) HyperExecute CLI"
