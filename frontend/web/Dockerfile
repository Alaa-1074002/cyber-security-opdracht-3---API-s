FROM node:22.15.1-slim 

WORKDIR /

COPY package.json .
COPY package-lock.json .
RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]