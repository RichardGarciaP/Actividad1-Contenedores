FROM node:18.0.0-alpine

WORKDIR /var/www/nodejs-app
EXPOSE 3000

COPY ./nodejs-app .

RUN npm install

CMD ["node", "src/index.js"]
