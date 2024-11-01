FROM node

WORKDIR /second

COPY package.json /second

RUN npm install

COPY . /second

EXPOSE 80

CMD [ "node", "server.js" ]

#docker build .
#docker run -p 3001:80 sha256:0d7b939ced10e896d428209e58edd58e868464b172d0138fde55206a8fafc50d
