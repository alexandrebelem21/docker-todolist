FROM mjgargani/puppeteer:trybe1.0

ADD node_modules.tar.gz ./
COPY . /tests

WORKDIR /tests

RUN npm install

CMD ["npm", "test"]