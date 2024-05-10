FROM node:20.11.1-slim

WORKDIR /app
COPY package.json index.js index.html ./
RUN npm install

EXPOSE 8080
CMD ["node", "index.js"]

# http://localhost:8080
# http://localhost:9090

