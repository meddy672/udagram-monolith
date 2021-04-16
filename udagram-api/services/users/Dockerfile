FROM node:11.15.0

WORKDIR /usr/app/src

COPY udagram-api/services/users/package*.json .

RUN  npm install

RUN  npm run build

COPY ./udagram-api/services/users/www .

EXPOSE 8080

CMD ["node", "server.js"]