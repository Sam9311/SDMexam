FROM node 18
WORKDIR /app
COPy package.json /app
RUN npm install
COPY  . /app 
CMD node server.js
EXPOSE 8080
     
