FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "server.js"]

#docker build .
#docker run -it sha256:5c574e89abbcd5167bb47e283352ac62879b950bc026cab59f7bb4f3daa2bf66

#docker run -p 3003:3000

#docker build -t bmi-app:l .
#isim ver
