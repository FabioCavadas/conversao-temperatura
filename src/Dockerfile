FROM node:12.22.12                
WORKDIR /app
COPY package*.json ./
RUN npm install 
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]