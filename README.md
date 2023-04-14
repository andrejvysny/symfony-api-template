# symfony-api-template

# Composer 
Install composer 
```bash
docker compose run cli composer install
```

# JWT
generate JWT keypair
```bash
docker compose run cli php bin/console lexik:jwt:generate-keypair
```

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