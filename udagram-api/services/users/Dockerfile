FROM node:11.15.0

WORKDIR /usr/app/src

COPY . .

RUN  ["npm install", "npm build"]

EXPOSE 8080

CMD ["node", "server.js"]