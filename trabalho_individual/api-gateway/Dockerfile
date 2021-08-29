FROM node:12.14.0

WORKDIR /api-gateway
COPY . /api-gateway/

RUN yarn

COPY . /api-gateway/

EXPOSE 7100

CMD yarn watch