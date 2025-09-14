FROM mcr.microsoft.com/devcontainers/cpp:latest

RUN apt-get update \
 && apt-get install -y libevent-dev python3-requests daemon \
 && useradd -r -s /bin/false portcheck