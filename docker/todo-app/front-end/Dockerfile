FROM node:14-alpine
LABEL info="Learning how to dockerize my apps 🐳"

WORKDIR /front-end

ADD node_modules.tar.gz .

COPY . .

EXPOSE 3000

ENTRYPOINT [ "npm", "start" ]