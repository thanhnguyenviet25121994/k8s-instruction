# Start with the official Ubuntu base image
FROM ubuntu:latest

# Set the maintainer label (optional)
LABEL maintainer="your-email@example.com"

# Update package list and install curl, nano, ssh, telnet, ping, and ip
RUN apt-get update && \
    apt-get install -y \
    curl \
    nano \
    openssh-client \
    telnet \
    iproute2 \
    iputils-ping \
    && apt-get clean

# Set the default command (optional)
CMD ["bash"]

