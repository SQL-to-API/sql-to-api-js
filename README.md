# sql-to-api

SQL to API idea is to set convention that enables using SQL to query API for data. 

# sql-to-api-js

SQL is converted to API call in client side. sql-to-api-js converts SQL to JavaScript and fetch complete query.

`SELECT * FROM users` => `fetch('/api/users')`

`SELECT * FROM users WHERE name=Jack` => `fetch('/api/users&name=Jack')`

`SELECT * FROM users WHERE name=Jack ORDER BY age` => `fetch('/api/users&name=Jack').sort((userA,userB) => userA.age-userB.age)`

