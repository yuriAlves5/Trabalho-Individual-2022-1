FROM node:16.17.0-alpine as builder

RUN mkdir -p /app


WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH

COPY package.json /app


RUN npm install --silent

COPY . .

