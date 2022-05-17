FROM node:14-alpine
WORKDIR /back-end
COPY package*json ./
ADD node_modules.tar.gz .
EXPOSE 3001
RUN npm install
