FROM ubuntu

COPY . /git-stuff

WORKDIR /git-stuff

RUN apt update && export TERM=screen && apt install git docker -y && git clone https://github.com/waxes27dev-ops

WORKDIR /git-stuff/dev-ops

RUN chmod +x git/* && bash git/build-all.sh

CMD bash

