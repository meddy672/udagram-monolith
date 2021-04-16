FROM node:11.15.0

WORKDIR /usr/app/src

COPY udagram-api/services/feed .

RUN  npm install

RUN  npm run build

COPY ./udagram-api/services/feed/www .

EXPOSE 8080

CMD ["node", "server.js"]