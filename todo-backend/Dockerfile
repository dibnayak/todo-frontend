FROM node:14
WORKDIR /usr/src/app
COPY package.json ./
COPY package-lock.json ./
RUN npm install
RUN npm init -y
COPY . .
EXPOSE 8080
CMD [ "node", "index.js" ]
