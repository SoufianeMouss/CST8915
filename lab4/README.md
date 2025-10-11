# Lab 4 - CST8915 Full-stack Cloud-native Development: Introduction to Docker

## Video
[Lab 4 Video](https://www.awesomescreenshot.com/video/45169094?key=cfaf421b989292053dbc736648c084f1)
## The main differences between a Docker image and a Docker container?
The Docker image is a lightweight package that includes everything we need to run an application such as libraries, runtime. we create it from Dockerfile and it's built in layers.
In the other hand a docker container is a running instance of a docker image. When we run it Docker add a writable layer on top of the image layers which make the container to run

## How Docker's layered architecture improves efficiency ?
Docker's layered architecture improves efficiency by reusing common layers which minimize the storage and optimize performance by speeding up builds and deployments

## Why does each container gets its own writable layer?
Each container gets its own writable layer because it runs independently from other containers and make changes without affecting others.
## What are the benefits of using Docker Compose over running containers individually?
The benefits of using Docker Compose is to run multiple containers simultaneously using YAML file.