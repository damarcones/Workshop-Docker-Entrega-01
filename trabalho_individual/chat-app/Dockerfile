FROM node:12.14.0

WORKDIR /chat-app
COPY . /chat-app/

RUN yarn

COPY . /chat-app/

EXPOSE 7101

CMD yarn watch 