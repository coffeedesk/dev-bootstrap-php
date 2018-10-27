# Bootstrap for php-based projects 

This is the bootstrap for php project which may be used with docker. It has nginx frontend configured too.

## Available containers

- `app` Based on https://github.com/coffeedesk/devops-docker-images/blob/master/php7/Dockerfile
- `nginx` Based on nginx:latest

## Local development
 
Run via docker-compose 
```
docker-compose up
```

Access with http:
```
curl localhost:<dynamically-assigned-port>
```
