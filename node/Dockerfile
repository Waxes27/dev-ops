FROM debian:latest

COPY . /app

WORKDIR /app

RUN apt update && apt install nodejs git curl -y && curl https://www.npmjs.com/install.sh | sh

WORKDIR /app/website

RUN npm i npm@latest -g && npm i

CMD npm start

