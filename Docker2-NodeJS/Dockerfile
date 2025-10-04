FROM node:18.0.0-alpine

WORKDIR /var/www/nodejs-app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "src/index.js"]
