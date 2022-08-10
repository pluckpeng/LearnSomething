## Docker
Docker is cool. Now image it if you and your friends are doing a WEB project. You guys have done all the codes. It's time to deploy it on the server. Image it you will still have a lot to do like configuring the environment and components like database and dependencies to systhesise with the development environment. But with docker you don't have to do all this trivials. All you need to do is upload your packed file to the docker hub then download it on the server with some simple cmds. REALLY COOL. I'm gonna try this in my next course project. 

*BUILD, SHIP and RUN!*

## Introduction.
Docker is more like a mini-OS. It is responsible for the management of both resources and processes. Because of the consistency of the process of build and deploy, the whole development process is largely compressed. You don't have to concern with the details but just focus on your work. If you are still confused after reading some docs about docker, just treat it as a program level maven as the real maven only provide dependencies and plugins.

## Usage
For the installation part, please check the official docs. Now let's talk about the usage of docker. First, as what I've stated above, docker is a mini-OS. To use it, you have to prepare some instructions. That is the Dockerfile. Dockerfile is the configuration file of docker, which contains all you need to do with a program including the whole lifecycle of the project(because it allows customized CMD, so almost you can do it with anything about the development).

Except the Dockerfile, docker-compose is even more powerful. docker-compose allows you to run multiple services together with individual configuration. Like you can run 5 Mysql servers at the same time on the different port on your computer with different configuration. That is, if you have a WEB project, you can compressed the whole project including the backend, frontend and database into one docker-compose file(be sure to set up your own image of backend and frontend by uploading your local projects).
