### Usage of Docker container of postgreSQL

```bash
docker-compose up -d # Runs the containers
```

```bash
docker-compose down # Stops the containers
```

> You can access a db manager on http://localhost:3200


| Property      | Value |
|    :----:   |    :----:   |
| server      | dockerized-postgresql-db-server:5432       |
| user   | postgres        |
| password   | postgres-pass        |
| database   |postgres     |