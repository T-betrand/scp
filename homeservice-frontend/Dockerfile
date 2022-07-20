FROM node:alpine
WORKDIR /homeserviceMPA 
RUN ls
ENV PATH="./node_modules/.bin:$PATH" 
COPY . .
RUN npm run build 