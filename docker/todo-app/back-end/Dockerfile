FROM node:14-alpine
LABEL info="Learning how to dockerize my apps 🐳"

WORKDIR /back-end

ADD node_modules.tar.gz .

COPY . .

EXPOSE 3001

ENTRYPOINT [ "npm", "start" ]