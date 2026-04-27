<img src="https://capsule-render.vercel.app/api?type=waving&color=F80000&height=160&section=header&text=bases-datos&fontSize=34&fontColor=FFFFFF&fontAlignY=40&desc=Bases%20de%20Datos%20%7C%20UAH%202025-26&descAlignY=60&descColor=FFCCCC" width="100%"/>

<div align="center">

![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-1D9E75?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![UAH](https://img.shields.io/badge/UAH-GII-085041?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-1D9E75?style=for-the-badge)

</div>

---

## About

**Asignatura:** Bases de Datos · UAH GII · Curso 2025-26

Relational database design and implementation: ER modelling, SQL querying, PL/SQL programming, triggers, user management and Python database connectivity.

---

## Topics covered

| Topic | Content |
|-------|---------|
| Relational model | ER design, normalisation (1NF, 2NF, 3NF, BCNF) |
| SQL | SELECT, JOIN, subqueries, aggregations, window functions |
| PL/SQL | Procedures, functions, cursors, exception handling |
| Triggers | BEFORE/AFTER, row-level, audit triggers, business logic |
| Users and security | RBAC, GRANT/REVOKE, role hierarchy |
| Transactions | COMMIT, ROLLBACK, isolation levels, ACID properties |
| Python connector | cx_Oracle, parameterised queries, connection pooling |

---

## Practices

| # | Name | Description |
|---|------|-------------|
| PL1 | ER design | Relational model design and DDL creation |
| PECL2 | [f1-database](./pecl2-f1/) | F1 relational DB with 589K lap records, 11 tables, complex queries, audit triggers, RBAC roles and Python connector |

---

## Database stats (F1 practice)

| Table | Records |
|-------|---------|
| circuitos | 77 |
| temporadas | 75 |
| escuderias | 212 |
| pilotos | 861 |
| gps | 1,125 |
| pilotos_corren_gps | 26,685 |
| pilotos_califican_gps | 10,494 |
| vueltas | 589,081 |
| pit_stops | 11,371 |

---

## RBAC roles

| Role | Permissions |
|------|-------------|
| admin | Full DDL + DML |
| gestor | DML only (no DDL) |
| analista | SELECT all tables |
| invitado | SELECT results, pilots, circuits — no lap times, no pit stops |

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=F80000&height=100&section=footer" width="100%"/>

*Bases de Datos · UAH GII · 2025-26*
</div>
