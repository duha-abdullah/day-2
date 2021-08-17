FROM node:10-alpine
WORKDIR /usr/src/app
COPY frontend/package*.json ./
RUN npm install
COPY frontend ./
EXPOSE 80