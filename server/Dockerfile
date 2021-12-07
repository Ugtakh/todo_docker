FROM alpine:3.12

WORKDIR /usr/src/todo

COPY package.json .

RUN apk add --update nodejs npm && npm install

COPY . .

EXPOSE 8000

CMD ["node", "server.js"]