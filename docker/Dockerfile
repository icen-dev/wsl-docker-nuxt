FROM node:16.0.0-alpine

RUN apk update && \
    npm install -g npm \
    npm install -g firebase-tools \
    && rm -rf /var/lib/apt/lists/*

ENV HOST 0.0.0.0
EXPOSE 3000
