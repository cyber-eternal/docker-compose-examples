# Docker and Docker Compose Examples

## Existing examples

- [Node.js](https://github.com/cyber-eternal/docker-compose-examples/blob/master/nodejs)
- [Mongodb](https://github.com/cyber-eternal/docker-compose-examples/blob/master/mongodb/docker-compose.yml)
- [MariaDB](https://github.com/cyber-eternal/docker-compose-examples/blob/master/mariadb/docker-compose.yml)
- [MySQL](https://github.com/cyber-eternal/docker-compose-examples/blob/master/mysql/docker-compose.yml)
- [MsSQL](https://github.com/cyber-eternal/docker-compose-examples/blob/master/mssql/docker-compose.yml)
- [Postgres](https://github.com/cyber-eternal/docker-compose-examples/blob/master/postgres/docker-compose.yml)
- [Oracle](https://github.com/cyber-eternal/docker-compose-examples/blob/master/oracle/docker-compose.yml)
- [Mongodb](https://github.com/cyber-eternal/docker-compose-examples/blob/master/mariadb/docker-compose.yml)
- [RabbitMQ](https://github.com/cyber-eternal/docker-compose-examples/blob/master/rabbitmq/docker-compose.yml)
- [Redis](https://github.com/cyber-eternal/docker-compose-examples/blob/master/redis/docker-compose.yml)
- [ElasticSearch](https://github.com/cyber-eternal/docker-compose-examples/blob/master/elasticsearch/docker-compose.yml)
- [Keycloak](https://github.com/cyber-eternal/docker-compose-examples/blob/master/keycloak)
  - [Keycloak with MySQL](https://github.com/cyber-eternal/docker-compose-examples/blob/master/keycloak/keycloak-mysql/docker-compose.yml)
  - [Keycloak with MsSQL](https://github.com/cyber-eternal/docker-compose-examples/blob/master/keycloak/keycloak-mssql/docker-compose.yml)
  - [Keycloak with Postgres](https://github.com/cyber-eternal/docker-compose-examples/blob/master/keycloak/keycloak-postgres/docker-compose.yml)
  - [Keycloak with Oracle](https://github.com/cyber-eternal/docker-compose-examples/blob/master/keycloak/keycloak-oracle/docker-compose.yml)
  - [Keycloak with MariaDB](https://github.com/cyber-eternal/docker-compose-examples/blob/master/keycloak/keycloak-mariadb/docker-compose.yml)

### Command to run an example

```bash
docker-compose up
```

### Command to run in background

```bash
docker-compose up -d
```

### Command to run after adding changes in docker-compose file

```bash
docker-compose up -d --build
```
