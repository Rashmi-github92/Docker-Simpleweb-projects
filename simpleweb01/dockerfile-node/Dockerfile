#Specify Base image
From node:alpine

WORKDIR /usr/app 

#Install dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

#Deafault command
CMD ["npm", "start"]
