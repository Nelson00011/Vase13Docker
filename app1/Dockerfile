FROM node:14

WORKDIR /app1

COPY package.json . 

RUN npm install

COPY . . 

EXPOSE 3000

CMD ["node", "app.mjs"]