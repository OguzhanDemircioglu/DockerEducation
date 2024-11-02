FROM node:14

WORKDIR /reactApp

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]

#docker build -t frontend .

#docker run --name frontend-cont --rm -p 3000:3000 -it frontend

