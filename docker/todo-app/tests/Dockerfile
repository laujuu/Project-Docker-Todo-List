
FROM mjgargani/puppeteer:trybe1.0

WORKDIR /todo-app/tests/

COPY package*.json ./
ADD node_modules.tar.gz .

RUN npm install

COPY . ./

EXPOSE 3000

ENTRYPOINT [ "npm" ]
CMD [ "test" ]