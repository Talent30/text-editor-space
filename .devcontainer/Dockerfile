# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.177.0/containers/alpine/.devcontainer/base.Dockerfile

# [Choice] Alpine version: 3.13, 3.12, 3.11, 3.10
ARG VARIANT="3.16"
FROM mcr.microsoft.com/vscode/devcontainers/base:0-alpine-${VARIANT}

# ** [Optional] Uncomment this section to install additional packages. **
# RUN sed -i -e 's/v[[:digit:]]\..*\//latest-stable\//g' /etc/apk/repositories
RUN apk update && apk upgrade -a && apk add fish nano nodejs
