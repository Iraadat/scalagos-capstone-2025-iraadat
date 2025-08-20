FROM node:17-alpine

WORKDIR /app
ARG ATLAS_URI

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5050

ENV ATLAS_URI=mongodb+srv://Iraadat:Finance001@cluster0.hrkvsgq.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0

CMD ["npm", "run", "start"]