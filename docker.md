
## Dockerfile
List of command sent to docker engine. Looks like a bash script, the engine execute it from the top to the bottom.

```javascript
FROM node:12.16.3 // node.js - image name; 12.16.3 - latest LTS version

WORKDIR /code //create this dir as working dir for all scripts

ENV PORT 80 //ENV VAR for any process in image

COPY package.json /code/package.json

RUN npm install //docker will execute it, npm will find package.json to install dependencies

COPY . /code //copy everything from working dir to the image. .dockerignore will help to ignore something you don't want

CMD ["node", "src/server.js"] //give cmd the engine telling it to find the node container and boot it with src/server.js


```



