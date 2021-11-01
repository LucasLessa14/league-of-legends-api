FROM node:16.13.0-alpine

WORKDIR /home/node/app

COPY package*.json ./

RUN npm install

COPY . . 

EXPOSE 4000

CMD ["npm", "run", "dev"]