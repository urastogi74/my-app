FROM node:14
WORKDIR /app

RUN npm init -y
RUN npm install
COPY . .
EXPOSE 3000

CMD ["node", "index.js"]
