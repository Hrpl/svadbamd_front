FROM node:latest
WORKDIR /app
COPY package.json .
RUN npm install react@17 react-dom@17
RUN npm install
COPY . .

EXPOSE 5173
CMD [ "npm", "run", "dev" ]