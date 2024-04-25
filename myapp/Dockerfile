FROM ubuntu
RUN apt update && \
    apt install -y nginx && \
    apt clean && \
    rm -rf /var/lib/apt/lists/*
COPY dep.yaml /path/inside/container/dep.yaml
