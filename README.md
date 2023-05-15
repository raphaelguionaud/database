# database

An attempt at building a simple database in C, for now closely following [cstack's tutorial](https://github.com/cstack/db_tutorial), which is based on SQLite. The goal is to understand what is happening in the database storage engine, as well as sharpen my C skills.

Questions going in:
* how is data really structured? (and how does SQL/noSQL fit into this)
* how is data indexed?
* what design tradeoffs are at play when creating a storage engine apart from read/write speed?

Planning to implement:
* optimised read/write speed
* indexing
* SQL queries

Features so far:
* command line REPL
