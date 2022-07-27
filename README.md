# SMS auth on Django Rest

## Usage

You should have poetry and docker installed

- Initialize environment and install dependencies

```
poetry install
```

- Create .env file in drf-sms-auth\config directory as in the example

- Run database

```
docker-compose --env-file drf-sms-auth\config\.env up
```

- Apply migrations

```
python manage.py migrate
```

- Run server and check docs at localhost:8000/swagger or redoc

```
python manage.py runserver
```
