FROM node: 14

WORKDIR /app4

COPY package.json .

RUN npm install

COPY . . 

EXPOSE 80

VOLUME ["/app/feedback"]

CMD [ "node", "server.js" ]

