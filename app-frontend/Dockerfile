FROM node:18-slim

WORKDIR /usr/app

COPY ./package.json .
COPY ./yarn.lock .

RUN yarn install

COPY . .

EXPOSE 3000

CMD [ "yarn", "start" ]