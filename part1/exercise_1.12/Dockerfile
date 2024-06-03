FROM node:16

EXPOSE 5000

WORKDIR /usr/src/app

COPY package*.json .

RUN npm install

COPY . .

RUN npm run build

RUN npm i -g serve

CMD ["serve", "-n", "-s", "-l", "5000", "build"]