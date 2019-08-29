# Traefik Demonstration

## Prerequisites

- Install Docker
- Install docker-compose
- Add line in your hosts file, in order to redirect docker.localhost to 127.0.0.1

## Configuration

Feel free to play with traefik config file to discover.

## Simulate Nginx on a remote server 

    docker run -p42837:80 -d nginx

## Urls availables

- nginx.docker.localhost (file)
- blog.docker.localhost (docker)
- tech.docker.localhost
- phpmyadmin.docker.localhost
- traefik.docker.localhost
- kibana.docker.localhost
