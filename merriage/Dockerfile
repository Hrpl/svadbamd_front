FROM node:latest
WORKDIR /app
COPY package.json .
RUN npm i --legacy-peer-deps
COPY . .

EXPOSE 5173
CMD [ "npm", "run", "dev" ]