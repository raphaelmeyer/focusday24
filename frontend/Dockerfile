FROM focusday24:latest

# Here you can extend the image with frontend specific libraries and tools

USER root

RUN curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - && apt-get update && apt-get install -y nodejs

USER dev
