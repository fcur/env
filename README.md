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

### Message broker

#### Apache Kafka
- **ZookeperHost**: 'localhost'
- **ZookeperPort**: '2181'
- **BrokerEndpoints**: '0.0.0.0:9092'
