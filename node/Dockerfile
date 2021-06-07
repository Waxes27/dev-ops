FROM node:alpine

COPY . /app

WORKDIR /app

RUN apt install npm git -y && git clone https://github.com/waxes27/website

WORKDIR /app/website

RUN npm i

CMD npm start

