FROM node:lts-alpine
RUN npm install -g http-server
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 8080
CMD [ "npm", "run", "serve" ]
