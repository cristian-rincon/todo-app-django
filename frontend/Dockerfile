# Use an official node runtime as a parent image
FROM node:lts-alpine

WORKDIR /app/

# Install dependencies
# COPY package.json yarn.lock /app/


# Add rest of the client code
COPY . /app/
RUN npm install

EXPOSE 3000

CMD npm start