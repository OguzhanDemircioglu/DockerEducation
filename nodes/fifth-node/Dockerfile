FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

CMD ["node", "app.js"]

#docker build -t feedback:volumes .

#docker run -d -p 3000:80 --rm --name mongodb


