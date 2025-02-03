FROM node:14
WORKDIR /app
COPY . .
RUN npm init -y
RUN npm install

EXPOSE 3000

CMD ["node", "index.js"]
