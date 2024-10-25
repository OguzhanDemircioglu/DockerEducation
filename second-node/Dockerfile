FROM node:22.5.1

WORKDIR /app

COPY . /app

RUN npm install

EXPOSE 80

CMD [ "node", "server.js" ]

#docker build .
#docker run -p 3000:3000 node-app
