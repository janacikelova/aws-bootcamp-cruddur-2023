FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

ENV AWS_CLI_AUTO_PROMPT=on-partial

WORKDIR /tmp
RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip" && \
    unzip awscliv2.zip && \
    sudo ./aws/install && \
    rm -rf awscliv2.zip aws