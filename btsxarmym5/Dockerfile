# stage 1

FROM node:18-alpine as builder
WORKDIR /app
COPY package.json .
RUN npm install
COPY ./src/ .
COPY ./public/ .
EXPOSE 3000

CMD [ "npm", "start" ]
