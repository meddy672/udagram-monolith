FROM node:11.15.0

WORKDIR /usr/app/src

COPY udagram-api/services/feed/www/package.json .

RUN  npm install

COPY ./udagram-api/services/feed/www .

EXPOSE 8080

CMD ["node", "server.js"]