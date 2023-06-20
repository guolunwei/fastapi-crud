# fastapi-crud
Developing and Testing an Asynchronous API with FastAPI and Pytest.

## Project Setup
```
docker compose up -d --build
```
check before continuing
```
http://localhost:8002/ping
http://localhost:8002/docs
```

# Test Setup
```
docker compose up -d --build
docker compose exec web pytest .
```

# Postgres Setup
```
docker compose up -d --build
docker compose exec db psql --username=hello_fastapi --dbname=hello_fastapi_dev
```

```
\l
\c hello_fastapi_dev
\dt
\q
```

# Clear environment
```
docker compose down
```
