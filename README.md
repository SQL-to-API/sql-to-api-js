# sql-to-api-js

[sql-to-api project](https://github.com/SQL-to-API/sql-to-api)

SQL is converted to API call in client side. sql-to-api-js converts SQL to JavaScript and fetch complete query.

`SELECT * FROM users` => `fetch('/api/users')`

`SELECT * FROM users WHERE name=Jack` => `fetch('/api/users?name=Jack')`

`SELECT * FROM users WHERE name=Jack ORDER BY age` => `fetch('/api/users?name=Jack').sort((userA,userB) => userA.age-userB.age)`

