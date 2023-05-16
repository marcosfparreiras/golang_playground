# What is this
This is a simple project to explore basic concepts of Golang

# Main sorce
- https://go.dev/learn/#tutorials
- https://go.dev/doc/tutorial/getting-started

# How to run it
## 1. Simply running the go application
1. Build the docker image
```sh
docker-compose build go
```
2. Run the code
```sh
docker-compose run go go run hello.go
```
## 2. Accessing the golang container to play inside it
```sh
docker-compose run go bash
```
