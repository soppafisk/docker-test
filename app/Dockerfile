FROM node:alpine

WORKDIR /usr/src/app

COPY src .
RUN npm install
RUN ls -lah

EXPOSE 8080
CMD [ "npm", "start" ]
