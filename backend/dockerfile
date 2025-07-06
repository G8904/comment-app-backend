<<<<<<< HEAD

FROM node:18-alpine
=======
FROM node:18
>>>>>>> dbb7383682cb78d798b57f1bcf4d2d3bd7c7ef5d
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build
<<<<<<< HEAD
EXPOSE 3000
=======
>>>>>>> dbb7383682cb78d798b57f1bcf4d2d3bd7c7ef5d
CMD ["npm", "run", "start:prod"]
