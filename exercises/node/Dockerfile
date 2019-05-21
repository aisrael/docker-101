FROM node:8.16.0-alpine

LABEL maintainer="Alistair A. Israel <me@alistairisrael.com>"

RUN mkdir /app
WORKDIR /app

COPY . .

EXPOSE 3000
CMD [ "node", "app.js" ]
