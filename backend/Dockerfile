FROM node:18-alpine

WORKDIR /app

# Optimisation cache
COPY package*.json ./
RUN npm install

# Copier le code
COPY . .

EXPOSE 3000
CMD ["npm", "start"]
