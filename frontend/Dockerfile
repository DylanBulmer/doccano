FROM node:13.7-alpine

WORKDIR /src

COPY . .

RUN yarn install \
  && yarn build

CMD npm run start