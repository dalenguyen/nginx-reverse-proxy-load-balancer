# Docker Nginx Reverse Proxy - Load Balancer

Sample code for setting up Nginx reverse proxy & load balancer with Docker

## Getting started

### Build reverse-proxy image from Dockerfile

```sh
docker build -t reverseproxy .
```

### Start servers with reverseproxy image

```sh
docker-compose up --build
```

Tear down the containers

```sh
docker-compose down
```

## Testing

- Nginx server: http://localhost:8080
- Apache server: http://localhost:8081
- Load balancer: http://localhost:8082

## Reference

[BogoToBogo](https://www.bogotobogo.com/DevOps/Docker/Docker-Compose-Nginx-Reverse-Proxy-Multiple-Containers.php)