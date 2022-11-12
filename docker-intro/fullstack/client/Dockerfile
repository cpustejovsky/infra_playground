FROM node

WORKDIR /client

COPY package*.json /client/

RUN npm install

#Copy content of directory into new directory
COPY . /client/

EXPOSE 3000

CMD ["npm", "start"]