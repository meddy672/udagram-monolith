FROM node:11.15.0

WORKDIR /usr/src/app

COPY udagram-api/services/users/package.json .

COPY . .

RUN  npm install

EXPOSE 8080

CMD ["node", "server.js"]