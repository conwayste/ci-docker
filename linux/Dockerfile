FROM rustembedded/cross:x86_64-unknown-linux-gnu

# needed for wireshark-common because it asks a question
ARG DEBIAN_FRONTEND=noninteractive

# https://docs.docker.com/develop/develop-images/dockerfile_best-practices/
RUN apt-get update && \
    apt-get install -yq libudev-dev libasound2-dev wireshark libglib2.0-dev && \
    rm -rf /var/lib/apt/lists/*
