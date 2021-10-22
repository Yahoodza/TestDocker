FROM node:14-alpine

COPY . /front/app

WORKDIR /front/app

RUN npm install -g @angular/cli
RUN npm install --dev

ENV PATH /front/app/node_modules/.bin:$PATH

CMD npm run start