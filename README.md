# Debezium CDC example

## Run

```bash
docker-compose up
```

Register the connector with

```bash
curl -i -X POST -H "Accept:application/json" -H "Content-Type:application/json" 127.0.0.1:8083/connectors/ --data "@register-postgres.json"
```

## Shutdown

```bash
docker-compose down --volumes
```
