# Docker Wordpress Proxy

docker-wordpress-proxy is a Dockerized WordPress website with an nginx reverse proxy, built from scratch to demonstrate Docker skills. It was made stricly for learning. For a final application, it's recommended to use the official WordPress image or modify this one implementing multi-stage builds and adding volumes for improved performance and scalability.

## Prerequisites
1. Docker and Git installed on your Linux-based system
2. Port 80 opened on your host

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/mmiazga99/docker-wordpress-proxy.git
    cd docker-wordpress-proxy/
    ```
2. Build and start the containers:
    ```sh
    docker-compose up -d
    ```
3. Verify that all containers are up and running:
    ```sh
    docker ps -a
    ```
4. Access the WordPress portal using your web browser:
    ```
    http://ip_of_your_machine:80/
    ```

## Cleaning Up
When you're done using the project, stop and remove the containers:
```sh
docker-compose down
