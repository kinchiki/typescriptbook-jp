FROM mcr.microsoft.com/playwright:v1.60.0-noble

WORKDIR /app
COPY package*.json ./
RUN npm install

COPY . .

# EXPOSE 5173

# CMD ["npm", "run", "test"]
