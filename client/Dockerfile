FROM node:14

WORKDIR /usr/src/app

COPY ./client/package.json ./

RUN npm install --legacy-peer-deps

COPY ./client .

EXPOSE 3000

CMD ["npm", "run", "start_docker_dev"]