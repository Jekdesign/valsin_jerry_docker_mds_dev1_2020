# DOCKER MERN - API REST PROJECT

:school: This DOCKER MERN API-RESTfull is a project school MBA 1st promotion :books:

## **🎬 Description**

Includes API endpoints handling for the client part:

Authentification (Sign-up & Login)

Posting articles (list, edit handling)
<br/>

## **🧱 Structure**

In folder server and client we will find a Dockerfile to build the image:

> ./backend/Dockerfile
>
> ./frontend/Dockerfile

In main repository we will find a docker-compose.yml to set containers launching:

> ./docker-compose.yml
> <br/>

## **⚙️ Composition de l'installation**

Dockerfile content:

> **FROM**: Use a lighter version of Node as a parent image
>
> **WORKDIR**: Set the working directory
>
> **COPY**: Copy the current directory contents into the container at /api
>
> **RUN**: install dependencies
>
> **EXPOSE**: Make port XXXX available to the world outside this container
>
> **CMD**: Run the app when the container launches

In docker-compose.yml:

_we will find there the version and the services of deployment_

## **:rocket: Install and Deployment**

> git clone https://github.com/Jekdesign/valsin_jerry_docker_mds_dev1_2020.git

Use docker:

> **docker-compose up --build** or **docker-compose up -d --build**
>
> _Shutdown if necessary: docker-compose down_

<br/>

Pactical basic for npm package manager

###### First, run the backend

> cd backend/
> npm install
> npm start
>
> ###### Then, run the frontend
>
> cd frontend/
> npm install
> npm start
> <br/>

:memo: Note:

- connection db: `mongodb://mongodb:27017`
- backend port listening: 8080
- client access: `https://localhost:3000`
  <br/>

## **💻 Technology**

- **Mongodb**
- **Express** _(node.js framework)_
- **React** _(front js framework)_
- **Node** _(tool javascript environment)_
- **Docker** _(CGROUP + Namespace)_
-
- **CGROUP** _(Partitioning resources - system, memory, networks)_
- **Namespace**
