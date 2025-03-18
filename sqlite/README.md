# SQLite3

SQLite. It's a lightweight, self-contained database that stores data in a single file. It's easy to use because:

- No need for a separate server process
- Uses a simple SQL interface
- The database is just a single .sqlite or .db file
- Works great for small applications, prototyping, and testing


## Instalation & Setup

Check if it is instaled (some linux flavors have by dafault)

```bash
sqlite3 --version
```

If not instaled, install it

```bash
sudo apt get update && sudo apt install sqlite3
```

To create a new database or open the sqlite console

```bash
sqlite3 my_database.db
```

## Run Commands From File

```bash
sqlite3 my_database.db < schema.sql
```

## CREATE TABLE

```sql
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,
   ....
);
```


## Data Types

SQLite has 5 primary data types:
- NULL It is a NULL value.
- INTEGER It is an integer, stored in 1, 2, 3, 4, 6, or 8 bytes depending on the value.
- REAL It is a floating point value, stored as an 8-byte floating number.
- TEXT It is a string, stored using the database encoding (UTF).
- BLOB It is a group of data, stored exactly as it was entered.


## Constraints

- NOT NUMM
- UNIQUE
- PRIMARY KEY
- FOREIGN KEY
- CHECK
- DEFAULT