FROM node

WORKDIR /first

COPY . /first

RUN npm install

EXPOSE 3000

CMD [ "node", "app.mjs" ]

#docker build .
#docker run -p --name tota 3000:3000 sha256:0d7b939ced10e896d428209e58edd58e868464b172d0138fde55206a8fafc50d