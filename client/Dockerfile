FROM node:alpine

WORKDIR /usr/src/app

COPY . .
ENV REACT_APP_BASE_URL=http://192.168.56.101:5000

RUN npm install

EXPOSE 3000

