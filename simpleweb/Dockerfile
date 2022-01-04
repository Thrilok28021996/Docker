# specify a base image

FROM node:ubuntu

# install dependencies
WORKDIR /usr/app
COPY ./package.json /usr/app

RUN npm install

COPY ./ ./

# default command
CMD ["npm","start"]