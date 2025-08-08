

## Create docker image

```shell
docker build -t my-hello-world .
```

## Test it locally
```shell
docker run -p 8080:80 my-hello-world
```
Open `http://localhost:8080`