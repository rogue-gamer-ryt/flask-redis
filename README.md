# Overview

This project is used to understand the various caching mechanisms and strategies. The use case is to have a flask app whose endpoints are cached.

# Tech Stack
- Flask
- Redis
- Flask-Caching (plugin)

# How to run it?

## Using `docker` 
You can run this project using its `docker-compose.yaml` and running this command
```docker
docker-compose up --build
```

## Using bash
1. Start the flask app
```bash
flask run
```
2. Start the redis server using docker
```
 docker run --name some-redis -d redis
```
