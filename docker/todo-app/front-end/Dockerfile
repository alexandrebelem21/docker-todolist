FROM node:14-alpine

ADD node_modules.tar.gz ./
COPY . /front-end

WORKDIR /front-end

RUN npm install

CMD ["npm", "start"]