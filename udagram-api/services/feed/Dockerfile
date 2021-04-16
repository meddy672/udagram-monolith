FROM node:11.15.0

WORKDIR /usr/app/src

RUN npm build

COPY ./udagram-api/services/feed/www .

RUN  npm install

EXPOSE 8080

CMD ["node", "server.js"]