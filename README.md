

```
podman exec -it db_mssql_server_1 bash

/opt/mssql-tools/bin/sqlcmd -S localhost -U sa -P "password123!" -Q 'SELECT 1'
```
