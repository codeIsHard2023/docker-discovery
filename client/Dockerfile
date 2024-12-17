FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY public public
COPY src src
COPY index.html index.html
COPY vite.config.js vite.config.js
CMD npm run dev