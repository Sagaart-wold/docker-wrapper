FROM node:20-slim as build

WORKDIR /usr/src/app
RUN mkdir -p $WORKDIR/static

COPY . .
RUN yarn install

RUN yarn run build
