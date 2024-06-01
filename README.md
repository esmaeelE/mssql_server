# Microsoft sql server dockerize

# Create, run and connect
```
podman-compose -f docker-compose.yml up -d 

podman exec -it db_mssql_server_1 bash

/opt/mssql-tools/bin/sqlcmd -S localhost -U sa -P "password123!" -Q 'SELECT 1'
```
