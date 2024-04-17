
FROM node:14-alpine

WORKDIR /lab_Task10_11/simple-reactjs-app

COPY package*.json ./

RUN npm install

COPY . .

RUN npm run build

EXPOSE 80

CMD ["npm", "run", "start"]
