FROM node:20-alpine3.19 AS base

WORKDIR /app

RUN apk add --no-cache \
    dumb-init \
    python3 \
    make \
    g++

RUN npm install -g @nestjs/cli --quiet

USER node

EXPOSE 3080

CMD ["/bin/sh"]
