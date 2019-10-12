# gobarber

Criando container postgres:

```shell
docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

Criando container mongodb:

```shell
docker run --name mongobarber -p 27017:27017 -d -t mongo
```

Criando container redis:

```shell
docker run --name redisbarber -p 6379:6379 -d -t redis:alpine
```

