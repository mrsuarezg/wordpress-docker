# WordPress - Docker Initial Base

This is a wordpress ready for deploy with Docker, MySQL and Ngnix.

## Comenzando 🚀

Clone or download this repository, remember can use git clone o wget.

```
    git clone https://github.com/mrsuarezg/wordpress-docker
```

### Pre-requisitos 📋

- Docker

```
https://www.docker.com/
```

### Instalación 🔧

_we will make a copy of the .env.example file includes by default and name the copy .env, which is the file expects to define its environment_

```
    cp .env.example .env
````

_With all of your services defined in your docker-compose file, you just need to issue a single command to start all of the containers, create the volumes, and set up and connect the networks:_

```
    docker-compose up -d
```

_Commands_

```
    docker-compose pause

    docker-compose unpause

    docker-compose down
```

_For the access use_

```
    http://localhost
```