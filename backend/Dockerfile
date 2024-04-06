FROM node:19-alpine
COPY . /app
WORKDIR /app
RUN npm i
RUN npm run build

CMD npm start