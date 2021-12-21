ARG NODE_VERSION=17-alpine3.12

FROM node:${NODE_VERSION}

WORKDIR /usr/src/app

COPY . .

RUN npm install

EXPOSE 8080
CMD ["node", "server.js"]