FROM node:6
WORKDIR /main
COPY package.json .
RUN npm install
RUN npm install -S sanitize-html
EXPOSE 3000
CMD node main.js
COPY . .