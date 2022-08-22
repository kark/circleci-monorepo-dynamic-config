FROM node:16.17.0
RUN mkdir -p /app
WORKDIR /app
COPY ./package.json ./
RUN yarn install
COPY . .
CMD [ "npm", "run", "start" ]