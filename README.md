
#   Base of a Django-Postgres Docker Compose Project
Base to start a project
1. Create venv
2. Create .env file with following attributes:
```
DJANGO_SECRET_KEY=...
DEBUG=True
DJANGO_LOGLEVEL=info
DJANGO_ALLOWED_HOSTS=localhost
DATABASE_ENGINE=postgresql_psycopg2
DATABASE_NAME=dockerdjango
DATABASE_USERNAME=...
DATABASE_PASSWORD=...
DATABASE_HOST=db
DATABASE_PORT=5432
```
3. `docker compose up -d --build`
<br>

Also:<br>
- Don't forget to docker compose down
- Track the versioning of both postgres and python docker images