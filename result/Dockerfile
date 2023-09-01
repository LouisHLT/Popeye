FROM node:12-alpine
WORKDIR /usr/src/app
COPY package.json ./
RUN npm install
EXPOSE 80
COPY server.js /usr/src/app/
CMD ["node", "server.js"]