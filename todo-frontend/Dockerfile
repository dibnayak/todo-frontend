FROM node:14
WORKDIR /usr/src/app
COPY package.json ./
COPY package-lock.json ./
RUN npm install
RUN npm i
COPY . .
CMD [ "npm", "run", "start" ]

