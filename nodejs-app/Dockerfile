FROM node:8.16-alpine

# Working directory
WORKDIR /usr/app 

COPY ./package.json ./ 

# Install node_modules dependencies
RUN npm install

COPY ./ ./


#Default command
CMD ["npm","start"]
