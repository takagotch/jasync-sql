### jasync-sql
---
https://github.com/jasync-sql/jasync-sql

```kt
Connection connection = MySQLConnectionBuilder.createConnectionPool(
  "jdbc:mysql://$host:$port/$database?user=$username&password=$password");

Connection connection = PostgreSQLConnectionBuilder.createConnectionPool(
  "jdbc://postgresql://$host:$port/$database?user=$username&password=$password");
  
CompletableFuture<QueryResult> future = connection.sendPreparedStatement("select * from table");
connection.disconnection().get()

```

```
```

```
```


