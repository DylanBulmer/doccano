FROM node:13.7-alpine

WORKDIR /src

COPY . .

RUN apk add git python3 make g++ \
  && yarn install \
  && yarn build \
  && apk del git make g++

CMD npm run start