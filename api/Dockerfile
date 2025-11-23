FROM node:alpine

LABEL version = "1"

WORKDIR /workdir/timeapp

COPY . /workdir/timeapp/

RUN npm install 

EXPOSE 5000

CMD ["npm", "start"]