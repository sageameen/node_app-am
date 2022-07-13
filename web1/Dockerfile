FROM node:alpine

WORKDIR /usr/src/app
COPY ./package-lock.json ./
COPY ./package.json ./
RUN npm install
COPY ./index.js ./

CMD ["npm","start"]
