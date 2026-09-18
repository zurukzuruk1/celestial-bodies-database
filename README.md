# Celestial Bodies Database

Solution for the freeCodeCamp Relational Database course project **"Celestial Bodies Database"**.

`universe.sql` is a full PostgreSQL dump (schema + data) of the `universe` database:
- Tables: `galaxy_type`, `galaxy`, `star`, `planet`, `moon`
- Primary keys, foreign keys, `UNIQUE` and `NOT NULL` constraints as required by the project

## Restore

```bash
createdb universe
psql universe < universe.sql
```
