FROM node:alpine
WORKDIR /homeserviceMPA 
ENV PATH="./node_modules/.bin:$PATH" 
COPY . .
RUN npm run build 