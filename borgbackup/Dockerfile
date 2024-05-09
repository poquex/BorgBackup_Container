FROM debian:latest
LABEL maintainer="Joaquin Espinoza <joaquin.espinoza@protonmail.com>"

# Install necessary packages
RUN apt update && apt install -y \
    borgbackup \
    && rm -rf /var/lib/apt/lists/*

# Set up the working directory
WORKDIR /app

# Create a directory for the storage volume
RUN mkdir /storage1

