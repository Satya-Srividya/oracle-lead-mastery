# Day 1 - Oracle SQL Fundamentals

## Topics Covered

- What is SQL?
- SQL Execution Order
- WHERE vs HAVING
- GROUP BY
- Alias
- Cost Based Optimizer (CBO)
- Oracle Optimizer
- Execution Plan
- CRUD Operations

---

## Key Interview Questions

### What is SQL?

SQL is a declarative language used to communicate with relational databases.
The developer specifies *what* data is required, while Oracle determines *how* to retrieve it using the Cost Based Optimizer.

---

### CRUD Operations

- Create
- Read
- Update
- Delete

---

### Logical SQL Execution Order

1. FROM
2. WHERE
3. GROUP BY
4. HAVING
5. SELECT
6. ORDER BY

---

### Difference between WHERE and HAVING

WHERE filters rows before grouping.

HAVING filters groups after aggregation.

---

### Cost Based Optimizer

Oracle's Cost Based Optimizer evaluates different execution plans using statistics, indexes, data distribution, and available 
access paths to choose the most efficient execution plan.

---

## Status

✅ Completed
