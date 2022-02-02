FROM mjgargani/puppeteer:trybe1.0
LABEL info="Learning how to dockerize my apps 🐳"

WORKDIR /tests

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm", "test" ]