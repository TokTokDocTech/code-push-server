FROM --platform=linux/amd64 node:18.9.1

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3400

CMD ["npm", "run", "start:env"]
