# code from https://github.com/Larkenx/Rotten-Soup

FROM node:carbon-slim

COPY . /app

WORKDIR /app

RUN npm install vue-cli -g

RUN yarn install

# front-end
EXPOSE 8080 

# nodejs server backend
EXPOSE 5000 

CMD ["yarn", "serve"]