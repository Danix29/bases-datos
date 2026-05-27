<img src="https://capsule-render.vercel.app/api?type=waving&color=F80000&height=160&section=header&text=bases-datos&fontSize=30&fontColor=FFFFFF&fontAlignY=40&desc=BD%20%7C%20UAH%202025-26&descAlignY=60&descColor=FFCCCC" width="100%"/>

<div align="center">

![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-1D9E75?style=for-the-badge)
![UAH](https://img.shields.io/badge/UAH-GII-085041?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-5DCAA5?style=for-the-badge)

</div>

---

## About

**Asignatura:** Bases de Datos &middot; UAH GII &middot; Curso 2025-26

Relational database design and implementation. From Entity-Relationship modelling to SQL DDL/DML, constraints, triggers and role-based access control — applied to a real-world Formula 1 historical dataset (589 K lap records).

---

## Topics covered

| Block | Content |
|-------|---------|
| Data modelling | Data dictionary, Extended ER diagram, semantic assumptions, cardinalities |
| Relational model | ER-to-relational mapping, primary keys, foreign keys, normalisation |
| SQL DDL | `CREATE SCHEMA`, `CREATE TABLE`, FK constraints, `ON DELETE`/`ON UPDATE` rules |
| Bulk loading | `COPY` from CSV, temp schema → clean schema ETL, type casting, NULL handling |
| SQL DML | `SELECT`, `JOIN`, aggregates (`COUNT`, `SUM`, `MAX`, `MIN`), subqueries, `WITH`, views |
| Triggers | Audit trigger (INSERT/UPDATE/DELETE log with JSONB), points counter trigger (Upsert) |
| RBAC | Roles (`admin`, `gestor`, `analista`, `invitado`), `GRANT`/`REVOKE`, schema-level permissions |
| Python + DB | `psycopg2` connection, parameterised queries, role-aware interactive menu |

---

## Practices

| # | Name | Description | Stack |
|---|------|-------------|-------|
| PL1 | [f1-database](./pl1-f1-database/) | F1 database design: EER diagram, relational model, PostgreSQL DDL with two-phase ETL (PL1temp → pl1final), 10 CSV files, 589 K lap records, FK constraints | PostgreSQL · SQL |
| PL2 | [f1-queries](./pl2-f1-queries/) | 11 complex SQL queries (JOINs, aggregates, subqueries, CTEs, views), audit + points triggers, 4-role RBAC and Python `psycopg2` client with permission-aware menu | PostgreSQL · Python · SQL |

---

## Database stats (F1 dataset)

| Table | Records |
|-------|---------|
| circuitos | 77 |
| temporadas | 75 |
| escuderías | 212 |
| pilotos | 861 |
| grandes premios | 1,125 |
| resultados | 26,685 |
| clasificaciones | 10,494 |
| vueltas | 589,081 |
| pit stops | 11,371 |

---

## Project structure

```
bases-datos/
├── pl1-f1-database/
│   ├── PL1_base_de_datos_25_26.pdf      # Practice guide
│   └── PECL1_Nogal_Buchanan-2-9.pdf     # Submitted report
└── pl2-f1-queries/
    ├── Pl2_base_de_datos_25_26.pdf       # Practice guide
    └── PECL2_DelNogal_Buchanan-2-9.pdf   # Submitted report
```

---

## Authors

| Name | DNI |
|------|-----|
| Daniel Del Nogal Buchanan | 54010299C |

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=F80000&height=100&section=footer" width="100%"/>

*Bases de Datos &middot; UAH GII &middot; 2025-26*
</div>
