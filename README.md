# symfony-api-template


# Entities
Create database
```bash
docker compose run cli php bin/console doctrine:database:create
```

Edit or Create entity
```bash
docker compose run cli php bin/console make:entity {name}
```

Create migration
```bash
docker compose run cli php bin/console make:migration
```

Execute migration
```bash
docker compose run cli php bin/console doctrine:migrations:migrate
```