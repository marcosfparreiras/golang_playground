# What is this
This is a simple project to explore basic concepts of Golang.

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
# To run the example 1
docker-compose run go go run example1/hello.go
# output: "Hello, World!"

# To run the example 2
docker-compose run go go run example2/hello.go
# output: "Don't communicate by sharing memory, share memory by communicating."
```
## 2. Accessing the golang container to play inside it
```sh
docker-compose run go bash
```
