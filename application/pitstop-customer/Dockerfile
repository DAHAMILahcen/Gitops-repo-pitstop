# Definir image docker 
FROM node:10
WORKDIR /app/customer
COPY package.json ./
RUN npm install
COPY . .
CMD ["npm","start"]

