FROM node:14-alpine

COPY . /front/app

WORKDIR /front/app

RUN npm install

ENV PATH /front/app/node_modules/.bin:$PATH

CMD npm run start