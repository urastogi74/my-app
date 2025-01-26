FROM node
WORKDIR /app

COPY package*.json ./
COPY . .
EXPOSE 3000
RUN npm install


ENTRYPOINT start npm