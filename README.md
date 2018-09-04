# docker-laravel
A light Laravel development environment for Docker.

# Introduction
Includes latest Nginx, PHP, NodeJs, Mariadb

# Installation

##### Clone this repository to your project root directory.

```
git clone https://github.com/cookievu/docker-laravel.git
```

#####  Edit your environment
```
cd docker-laravel
```
```
cp .env.example .env
```

#####  Build images
```
docker-compose up -d --build
```

Done.

Enter to http://localhost & start to work

#####  More command

List running containers after created
```
docker ps
```

List all containers
```
docker ps -a
```

Stop an running container
```
docker stop [container ID or container name]
```

Stop all running container
```
docker-compose stop
```

Remove all containers
```
docker-compose down
```

# Troubleshooting

- Make sure there are no containers listening to the ports used with this setup
