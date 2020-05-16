# DOCKER MERN - API REST PROJECT

###### _:school: This DOCKER MERN API-RESTfull is a project school MBA 1st promotion :books:_

**🎬 Description**

_Includes API endpoints handling for the client part:_
_Authentification (Sign-up & Login)_
_Posting articles (list, edit handling)_

**🧱Structure**
In folder server and client we will find a Dockerfile to build the image:

> - ./backend/Dockerfile
> - ./frontend/Dockerfile

In main repository we will find a docker-compose.yml to set containers launching:

> - ./docker-compose.yml

**⚙️ Composition de l'installation**

#### Content Dockerfile

> _FROM_: Use a lighter version of Node as a parent image
> _WORKDIR_: Set the working directory
> _COPY_: Copy the current directory contents into the container at /api
> _RUN_: install dependencies
> _EXPOSE_: Make port XXXX available to the world outside this container
> _CMD_: Run the app when the container launches

#### docker-compose.yml

_we will find there the version and the services of deployment_

**:rocket: Install and Deployment**

> git clone https://github.com/Jekdesign/valsin_jerry_docker_mds_dev1_2020.git
>
> Use docker: docker-compose up --build or docker-compose up -d --build
>
> _Shutdown if necessary: docker-compose down_

> # Pactical basic for npm package manager\*
>
> ### First, run the backend
>
> cd backend/
> npm install
> npm start
>
> ### Then, run the frontend
>
> cd frontend/
> npm install
> npm start

:memo: Note:

- connection db : mongodb://mongodb:27017
- backend port listening: 8080
- client access: https://localhost:3000

_💻 Technology_

- **Mongodb**
- **Express** _(node.js framework)_
- **React** _(front js framework)_
- **Node** _(tool javascript environment)_
- **Docker** _(CGROUP + Namespace)_
-
- **CGROUP** _(Partitioning resources - system, memory, networks)_
- **Namespace**
