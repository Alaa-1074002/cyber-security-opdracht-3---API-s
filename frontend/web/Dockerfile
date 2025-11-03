FROM node:22.21.1-slim 

WORKDIR /

COPY package.json .
COPY package-lock.json .
RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]