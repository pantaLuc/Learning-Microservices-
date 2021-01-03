# base image 
FROM node:alpine 

WORKDIR /app
COPY package.json ./

# install aditional dependencies

RUN npm install

COPY ./ ./

#command to startup the container

CMD ["npm" ,"start"]