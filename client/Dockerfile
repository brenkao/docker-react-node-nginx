FROM node:alpine
WORKDIR /app
COPY package.json ./
COPY package-lock.json ./
COPY .babelrc ./
COPY ./ ./
RUN npm i
CMD ["npm", "run", "start"]
