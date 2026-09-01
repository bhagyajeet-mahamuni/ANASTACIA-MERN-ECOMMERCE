## Get the base image

FROM node:18-alpine

## Get the working directory

WORKDIR /app

## Copy the dependancies

COPY package*.json ./

## Install the dependancies

RUN npm install --lagacy-peer-deep

COPY . .


## Mention the port

EXPOSE 5000

## Run the application

CMD ["npm","start"]
