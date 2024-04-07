FROM node:alpine

WORKDIR /usr/src/app

COPY . .

RUN npm install

EXPOSE 5000

CMD ["npm", "start", "--", "--p", "5000", "--cp", "3000"]