#FROM node:boron
FROM mhart/alpine-node
#FROM mhart/alpine-node:base-6

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

# Install app dependencies
#COPY /opt/DockerWork/newsApiV3/node_modules /usr/src/app/
#RUN npm install

# Bundle app source
COPY . /usr/src/app

EXPOSE 4794


ENTRYPOINT ["node","server.js"]
# ["node", "index.js" ,"0.0.0.0","9000", "10.130.33.95" ,"tmp" , "debug"]
