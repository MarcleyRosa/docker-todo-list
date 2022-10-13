FROM node:14-alpine

WORKDIR /app
ADD node_modules.tar.gz .
COPY /src .

EXPOSE 3001
ENTRYPOINT ["npm", "start"]