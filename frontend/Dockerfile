# frontend/Dockerfile
FROM node:latest
 
WORKDIR /usr/src/app
 
COPY package*.json ./
 
RUN npm install -g live-server && npm install
 
COPY . .
 
EXPOSE 4000
 
CMD ["npm", "start"]