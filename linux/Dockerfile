FROM rustembedded/cross:x86_64-unknown-linux-gnu

# https://docs.docker.com/develop/develop-images/dockerfile_best-practices/
RUN apt-get update && \
    apt-get install -yq libudev-dev libasound2-dev && \
    rm -rf /var/lib/apt/lists/*
