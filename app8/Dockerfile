FROM node

WORKDIR /app8

COPY package*.json ./

RUN npm install

COPY . . /app8/

EXPOSE 80 

CMD ["node", "app.js"]
