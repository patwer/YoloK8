FROM node:12.22.9

WORKDIR /app

COPY package*.json /app/
RUN npm i

COPY . /app/

CMD ["npm", "start"]