# PostgreSQL Learnings

A practical collection of PostgreSQL examples and exercises for learning relational database fundamentals.

## Contents

The complete SQL learning guide is available in [main_sql_code.md](main_sql_code.md). It includes:

- Creating tables and inserting sample data
- Filtering, grouping, sorting, aliases, and aggregate functions
- Subqueries and conditional expressions
- One-to-one, one-to-many, and many-to-many relationships
- Primary keys and foreign keys
- Inner and left joins
- Views
- A PL/pgSQL stored procedure

## Requirements

- PostgreSQL 12 or newer
- A PostgreSQL client such as `psql`, pgAdmin, or DBeaver

## Quick Start

1. Create or connect to a PostgreSQL database.
2. Open [main_sql_code.md](main_sql_code.md).
3. Run the SQL examples in order, one section at a time.
4. Execute the practice questions and compare the results with the examples.

For a local database, you can connect with:

```bash
psql -U <username> -d <database_name>
```

## Learning Notes

The file is organized as a learning workbook rather than a production migration. Some sections reuse table names to demonstrate different database relationships, so run each section in a fresh database or reset the related tables before moving to another example.

## Project Structure

```text
.
├── README.md
├── main_sql_code.md
├── Orders_Table.csv
└── Products_Table.csv
```

## License

This project does not currently specify a license.