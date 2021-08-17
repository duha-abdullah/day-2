FROM node:10-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN ls -l
RUN npm install
COPY . ./
EXPOSE 80
CMD ["npm", "run"]
