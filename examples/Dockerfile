FROM node
WORKDIR /app

COPY package*.json ./
COPY . .
EXPOSE 3000
RUN npm install


CMD ["node", "index.js"]