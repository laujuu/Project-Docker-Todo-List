
FROM node:14-alpine

WORKDIR /todo-app/back-end/

COPY package*.json ./
ADD node_modules.tar.gz .

RUN npm install

COPY . ./

EXPOSE 3001

ENTRYPOINT [ "npm" ]
CMD [ "start" ]