FROM node:14-slim

WORKDIR /app

COPY package.json .
COPY . .

RUN npm install -g semistandard
RUN npm install

CMD ["node", "0-javascript_is_amazing.js"]
