FROM mcr.microsoft.com/vscode/devcontainers/python:3.10


USER root

RUN apt-get update && apt-get install -y sudo

# No need to create 'vscode' user, proceed with the default user
RUN echo "vscode ALL=(ALL) NOPASSWD: ALL" >> /etc/sudoers

USER vscode

WORKDIR /workspaces

# Install any necessary packages (optional)
RUN sudo apt-get install -y git

RUN pip install poetry

