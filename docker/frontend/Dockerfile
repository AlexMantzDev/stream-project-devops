FROM node:latest

WORKDIR /usr/src/app

COPY package.json .

RUN npm i

COPY ./dist .

EXPOSE 8081

CMD ["npm", "run", "serve"]