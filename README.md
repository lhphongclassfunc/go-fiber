## Start

```bash
Fast refresh golang app in development
install air: go install github.com/cosmtrek/air@latest
then Reload terminal
run command: air init
then run command to start server: air
Development evironment auto refresh when update code
```

```bash
# Install
go get .
# Run
go run .
or
go build -o server && ./server
```

## Test build on docker

```html

- Install docker: https://docs.docker.com/get-docker/

- Build docker images command: "docker build -t go_fiber_docker ."

- Run docker images command: "docker run go_fiber_docker"

- List images : docker images

```