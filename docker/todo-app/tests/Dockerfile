FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app
ADD node_modules.tar.gz .
COPY /src .

ENTRYPOINT ["npm", "test"]
