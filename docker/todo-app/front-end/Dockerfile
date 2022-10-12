FROM node:14-alpine

WORKDIR /todo-app/front-end
ADD node_modules.tar.gz .
COPY package-lock.json .
COPY package.json .
COPY /src /src

EXPOSE 3000
CMD ["npm", "start"]