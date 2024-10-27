FROM node

WORKDIR /first

COPY . /first

RUN npm install

EXPOSE 3000

CMD [ "node", "app.mjs" ]

#docker build .
#docker run -p 3000:3000 {{imgNumber}}
