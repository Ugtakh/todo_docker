FROM alpine:3.12

WORKDIR /usr/src/todo

COPY package.json .

RUN apk add --update && apk add nodejs && npm install

COPY . .

EXPOSE 8000

CMD ['npm', "start"]