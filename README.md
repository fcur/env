# Environment
Local environment templates.

## Create and start containers

```
 docker compose -f ./docker-compose-mssql.yml up
```

## Available templates

### SQL db

#### Microsoft SQL Server

- **Username**: 'sa'
- **Password**: 'Pass@word'
- **Port**: '1433'


#### PostgreSQL

- **Username**: 'postgres'
- **Password**: 'Pass@word'
- **Port**: '5432'

### NoSql db

#### MongoDB

- **Username**: 'LocalUser'
- **Password**: 'Pass@word'
- **Port**: '27017'
