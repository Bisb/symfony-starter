# Symfony Docker starter

## Installation

Adapt the `starter` name in `.env `, this will help naming the container for convenience

```shell
docker compose up -d
```

If you're planning on using this for development you can copy `docker-compose.dev.yml` into `docker-compose.override.yml` or specify the file to use with docker compose like so :
```shell
docker compose -f docker-compose.yml -f docker-compose.dev.yml up -d
```
