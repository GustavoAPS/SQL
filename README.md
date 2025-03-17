# SQL

SQL (Structured Query Language) is a standardized programming language used to store, retrieve, manage, and manipulate data in relational databases.

## Components

### DDL - Data Definition Language

Used to create components, common commands are:

- CREATE TABLE
- ALTER TABLE
- DROP TABLE
- CREATE INDEX
- ALTER INDEX
- DROP INDEX

### DML - Data Manipulation Language

Used to manipulate data stored in the database, some common commands are:

- Insert
- Delete
- Update

### DQL - Data Query Language

Used to extract data from the database, command:

- Select

### DCL - Data Control Language

Used to the internal security of the database, some of the common comands are:

- CREATE USER
- ALTER USER
- GRANT
- REVOKE
- CREATE SCHEMA

---

## Bancos de Dados & SQL


- Índices: Como funcionam, tipos (B-Tree, Hash, etc.), impacto na performance.
- N+1 Problem: Como identificar e resolver (Eager Loading, Lazy Loading, JOINs).
- Normalização vs. Denormalização: Vantagens e desvantagens.
- Transações e Locks: Isolation levels (Read Uncommitted, Repeatable Read, etc.).
- Consultas Otimizadas: EXPLAIN ANALYZE, índices compostos, CTEs.
- Bancos NoSQL: Quando usar MongoDB, Redis, DynamoDB.

👉 Problemas canônicos:

- Otimizar uma consulta lenta.
- Resolver um problema de N+1 em um ORM.
- Decidir entre normalização e denormalização para um caso real.