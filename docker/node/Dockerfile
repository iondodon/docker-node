FROM node:8

# Create app directory
WORKDIR /usr/src/app

RUN npm install -g nodemon
# If you are building your code for production
# RUN npm install --only=production

EXPOSE 8080

CMD [ "nodemon", "server.js" ]