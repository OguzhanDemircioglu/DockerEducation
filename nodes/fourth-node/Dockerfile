FROM node:14

ARG DEFAULT_PORT=80

WORKDIR /fourthNode

COPY package.json .

RUN npm install

COPY . .

EXPOSE $DEFAULT_PORT

#VOLUME ["/fourthNode/feedback"]   anonymous volume

CMD [ "npm", "start" ]

#docker build -t feedback:volumes .

#docker run -d -p 3000:80 --rm --name vollli -v feeback:/fourthNode/feedback -v "D:\Projeler\DockerEducation\nodes\fourth-node:/fourthNode" -v /fourthNode/node_modules feedback:volumes

#docker stop vollli

#docker volume rm feeback
#docker volume prune
#  -v "D:\Projeler\DockerEducation\nodes\fourth-node:/fourthNode"