FROM node:10

#Setup working directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

#Install dependencies
COPY package.json package-lock.json ./
RUN yarn install

#Copy source files
COPY . .

#Running the app
CMD ["yarn", "dev"]