FROM node:8
# Create app director
COPY package*.json ./

RUN npm install
COPY . .
RUN npm run build
EXPOSE 443
CMD [ "npm", "run", "start" ]