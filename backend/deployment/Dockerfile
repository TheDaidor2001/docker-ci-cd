FROM node:20-alpine

WORKDIR /src


COPY package*.json ./


RUN npm install


COPY src ./src
COPY tsconfig.json ./


RUN npm run build




CMD ["npm", "start"]
