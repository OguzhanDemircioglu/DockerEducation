FROM node:14

WORKDIR /backendApp

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

#ENV MONGO_USERNAME=cray61
#ENV MONGO_PASSWORD=1

CMD ["node", "app.js"]

#docker build -t backend .

#docker run --name backend-node --rm -d -p 80:80 backtend1




