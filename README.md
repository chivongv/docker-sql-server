### Connect on Linux

- requires package mssql-tools

```
$ sqlcmd -S localhost -U sa -C
1> Sp_databases
2> Go 
```

### Connect with SQL Server Management Studio
- use localhost,1433 as server name
- login credentials sa

### Connect on Windows

```
$ mssql -u sa
$ mssql> .databases
$ mssql> .run db_setup.sql
$ mssql> .tables
```
