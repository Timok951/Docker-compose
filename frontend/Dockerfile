FROM node:alpine

LABEL version = "1"

WORKDIR /workdir/timeapp

COPY . /workdir/timeapp/

RUN npm install

EXPOSE 8954

CMD ["npm","run", "dev"]