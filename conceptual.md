### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
- It is a relational database management system used to store, access, and manage data.

- What is the difference between SQL and PostgreSQL?
-  SQL is the language used to query the database, whereas PostgreSQL is the management system for the database itself.

- In `psql`, how do you connect to a database?
- $ \c 'database_name'

- What is the difference between `HAVING` and `WHERE`?
- `HAVING` groups by rows then filters
- `WHERE` filters rows then groups by

- What is the difference between an `INNER` and `OUTER` join?
- `INNER` joins table from intersecting data of tables
- `OUTER` joins all tables/data 

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
- `LEFT OUTER` returns data from the left of the table and intersecting data
- `RIGHT OUTER` return data from the right of the table and intersecting data

- What is an ORM? What do they do?
- Object relational mapper - translate the services between the OOP in a server language and the relational data in a database

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
- AJAX request are made from Javascript dirrect in the browser that allow the app to send requests and receive responses withouth having to reload the browser page

- What is CSRF? What is the purpose of the CSRF token?
- CSRF is a type of website exploitation where unauthorized code is transmitted from something such as hidden information in a form. A CSRF token is used in a form to verify that the information being responded with is originating from the app itself and not a malicious entity.

- What is the purpose of `form.hidden_tag()`?
- This is used in a form to place a hidden field such as a CSRF token that is not directly visible to the app user.