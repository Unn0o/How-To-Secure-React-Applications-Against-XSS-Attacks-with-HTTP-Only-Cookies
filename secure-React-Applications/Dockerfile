FROM node:18.7.0-bullseye

RUN apt update -y \
    && apt upgrade -y \
    && apt install -y vim nano \
    && mkdir /app

WORKDIR /app

CMD [ "tail", "-f", "/dev/null" ]