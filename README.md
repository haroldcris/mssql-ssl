### Running MSSQL in docker with SSL Encryption 

1. Register your domain by running certbot
```
docker compose run --rm cerbot

```

2. Run the container afterwards

```
docker compose up -d --remove-orphans

```
