FROM node:fermium-alpine3.14

WORKDIR /app

COPY . .

RUN yarn

EXPOSE 3000

CMD [ "node", "server.js" ]
