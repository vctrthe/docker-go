# Docker-Go

Docker Go is an application built with Golang, JWT, GORM, PostgreSQL.

## Information

I don't take any credits from this project!

All credits belongs to the [owner]:(https://levelup.gitconnected.com/crud-restful-api-with-go-gorm-jwt-postgres-mysql-and-testing-460a85ab7121)

## Project Information

First, please save ``.env.example`` as ``.env``

## How to use

### Running Production

```bash
docker-compose -f docker-compose.yml up --build
```

### Running Test

```bash
docker-compose -f docker-compose.test.yml up --build --abort-on-container-exit
```

### Stopping Application

```bash
docker-compose down
```