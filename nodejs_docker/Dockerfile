FROM node:14

WORKDIR /nodejs_docker
COPY package.json .
RUN npm install
COPY . .
CMD npm start
