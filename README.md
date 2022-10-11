## Start INSTEP API

```html
This is private repository because has GCP secret key
Don't public
```

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

- Build docker images command: "docker build -t api-instep ." (or build stg: "docker build -t api-instep -f Dockerfile-stg .")

- Run docker images command: "docker run api-instep" (or "docker run --publish 8080:8080 api-instep" (http://localhost:8080))

- List images : docker images

```

