# Dynamodb Set up

## Required

- docker
- docker compose

## Environment

| Variable            | Description             | Default |
|---------------------|-------------------------|---------|
| DYNAMODB_PORT       | Port for DynamoDB Local | 8000    |
| DYNAMODB_ADMIN_PORT | Port for DynamoDB Admin | 8001    |

## Installation

```bash
docker compose up -d
```

## Access

- http://localhost:${DYNAMODB_PORT} : DynamoDB Local
- http://localhost:${DYNAMODB_ADMIN_PORT} : DynamoDB Admin