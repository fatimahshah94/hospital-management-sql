# Hospital Management System – SQL Project

A relational database for a hospital system, built in MySQL as part of the
Atomcamp Data Analytics Bootcamp. The dataset was provided in the project brief
and is synthetic.

## What I built
**Part 1 – Database design**
- Created a schema with 8 tables: hospitals, doctors, patients, appointments,
  departments, medications, prescriptions and rooms
- Defined primary keys, foreign keys and data types to enforce referential integrity
- Loaded the data and validated it with SELECT checks

**Part 2 – Analysis queries (20+)**
- Filtering, sorting and aggregation (e.g. appointments per month, doctors per hospital)
- Multi-table joins (e.g. appointments with patient and doctor names)
- Subqueries and CTEs (e.g. patients who have never had a prescription)
- Window functions: `DENSE_RANK()` for the 3rd most prescribed medication and
  the second-largest department per hospital
- `CASE` logic to group emergency patients into Pediatric, Adult and Geriatric

## Skills used
MySQL · joins · GROUP BY / HAVING · subqueries · CTEs · window functions · CASE

## Files
- `project_data.sql` – table data provided in the brief
- `SQL_Project_-Fatima_Shah.sql` – my schema and queries

## How to run
1. Create a new schema in MySQL Workbench
2. Run the `CREATE TABLE` statements, then the data inserts
3. Run the queries in Part 2
