FROM node:10

# Setting working directory.
WORKDIR /next

# Installing dependencies
COPY package.json /next/
RUN npm install

# Copying source files
COPY . /next/

# Building app
RUN npm run build
