# specify base image

FROM node:alpine

# specify working directory

WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]