
FROM node:14-alpine

WORKDIR /todo-app/front-end/

COPY package*.json ./
ADD node_modules.tar.gz .

RUN npm install

COPY . ./

EXPOSE 3000

ENTRYPOINT [ "npm" ]
CMD [ "start" ]