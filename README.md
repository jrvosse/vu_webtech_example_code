Framework for Assignment 3: Web Technology at VU Amsterdam
==========================================================

This is a template to help you getting started with implementing a RESTful API
for Assignment 3. You are advised to:
* make a new folder for Assignment 3
* download the file `server.js` into this folder
* make sure you have the sqlite3, express and body-parser modules installed:

```bash
$ npm install sqlite3@5.0.0 express body-parser
```

Please read and try to understand the example code in `server.js`,
and see if you can make it run before you make any changes (see below).

Running the server
------------------

You can start the server on a command line (Terminal, Powershell) by executing:

```
$ node server.js
```

This starts a server responding to
[http://localhost:3000/hello](http://localhost:3000/hello) and
[http://localhost:3000/db-example](http://localhost:3000/db-example).
You can verify this with a browser.

Note that you need a REST client such as [`Postman`](https://learning.postman.com/) or `curl` to test HTTP methods other than GET!


Accessing the database
----------------------

The server automatically creates an SQLite database table 'products' in the file `products.db`, with one example entry for testing purposes.
This file is re-created whenever you delete it, and restart the server.

Using the db object, you can execute SQL queries and retrieve results. Have a look at the [documentation
of `sqlite3`](https://www.sqlitetutorial.net/sqlite-nodejs/).


Your task
---------

Now it's up to you to fill in the missing bits and pieces according to the design of your API
by adding appropriate routes. Also use the examples in the zyBook to create a package.json file that defines how to easily start and test your server.
