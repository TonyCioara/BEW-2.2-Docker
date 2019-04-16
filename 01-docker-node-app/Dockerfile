FROM node:8

# Create app directory
WORKDIR /Users/tonycioara/Desktop/BEW-2.2-Docker/docker_node_app

# Install app dependencies
COPY package*.json ./

RUN npm install

# Bundle app source
COPY . .

EXPOSE 8080

CMD ["npm", "start"]