## Local Service Run
# Postegres Set Up
```shell
docker build -t local-postgres ./infra/local/postgres
```

```shell
docker run -d \
  --name dev_postgres \
  -p 5432:5432 \
  -v postgres_data:/var/lib/postgresql/data \
  local-postgres
```