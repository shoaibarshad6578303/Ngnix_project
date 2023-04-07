FROM node:16

WORKDIR /user/scr/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 7777

CMD ["npm", "run", "start"]