from node:20
workdir /opt/app
copy package.json .
copy *.js .
RUN npm install
ENV MONGO='true' \
    mongoURL='mongodb://mongodb:27017/catalogue'
cmd [node, server.js]


