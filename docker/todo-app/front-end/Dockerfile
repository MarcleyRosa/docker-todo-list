FROM node:14-alpine

ENV REACT_APP_API_HOST="todobackend"

ENV REACT_APP_API_PORT=3001

WORKDIR /app
ADD node_modules.tar.gz .

COPY . .

CMD ["npm", "start"]

EXPOSE 3000