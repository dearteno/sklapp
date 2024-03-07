FROM node:lts-alpine

RUN mkdir -p /usr/src/app

WORKDIR /usr/src/app

COPY . .

RUN npm install

EXPOSE 8080

RUN chmod +x docker-entrypoint.sh

CMD npm start