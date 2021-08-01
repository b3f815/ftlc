FROM mongo-express

MAINTAINER befinbabu@gmail.com

WORKDIR /usr/src/backend-api

COPY package.json .

COPY index.js .env models ./

CMD ["/bin/bash"]

RUN npm install

EXPOSE 8001