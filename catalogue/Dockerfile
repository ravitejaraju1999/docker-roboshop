from node:20
workdir /opt/app
copy package.json .
copy *.js .
run npm install
env MONGO='true' \
    mongo_url="mongodb://mongodb:27017/catalogue"
cmd ["node", "server.js"]


