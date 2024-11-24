FROM node:20-slim as build

WORKDIR /usr/src/app

#ADD ./ ./
ADD *.json ./
ADD *.ts ./
ADD *.html ./
RUN npm install

ADD ./public ./public
ADD ./src ./src


#RUN npm run build