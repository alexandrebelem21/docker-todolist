FROM node:14-alpine

EXPOSE 3001

ADD node_modules.tar.gz /
COPY . /back-end

WORKDIR /back-end

RUN npm install

CMD ["npm", "start"]