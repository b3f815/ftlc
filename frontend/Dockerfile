FROM mongo-express

MAINTAINER befinbabu@gmail.com

WORKDIR /usr/src/frontend

COPY package.json .

RUN npm install

COPY index.js public views ./

CMD ["/bin/bash"]

EXPOSE 8000
