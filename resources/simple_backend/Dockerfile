FROM node

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

#Copy content of directory into new directory
COPY . .

EXPOSE 4000

CMD ["npm", "start"]