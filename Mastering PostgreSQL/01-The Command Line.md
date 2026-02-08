# The PostgreSQL Command Line

PostgreSQL comes with `psql`, the command line tool for managing postgreSQL servers using the terminal. You can start sessions using the command `psql -d <DBNAME>`.

After connecting to the db, use the `/?` command the see all of the available commands for the current database environment. It acts as a built-in cheat sheet so I do not have to memorize every single shortcut to navigate.

The `\\d` command allows you to see the structure of your data, you can see the current schema, tables, and relations. use the name of the entitiy you want more details about along with the command to get more details about it. Example, `\\d users` will show you a detailed blueprint of the users table, showing its columns, the type of data they hold, and any indexes associated with them.

By default, the output of `psql` isn't perfectly readable so you can type `\\x auto` to change the output results to be shown based on the screen size, switching views to show the output clearly.
