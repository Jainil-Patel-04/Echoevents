#Echo Events: An Event & Movie Ticketing Database Management System

A SQL-based relational database system developed with PostgreSQL to manage event ticketing and related operations. This project demonstrates robust database design principles, including ER modeling, normalization, and the use of DDL/DML scripts to build and interact with the database.

## 🔍 Features

1. *ER Modeling & Normalization*

   * Designed a detailed Entity-Relationship (ER) diagram to map events, venues, customers, tickets, and sales.
   * Normalized the schema to BCNF, minimizing redundancy and ensuring data integrity.
    
2. *PostgreSQL Implementation*

   * Created the full relational schema with DDL scripts, including tables, primary/foreign keys, and constraints.
   * Populated the database with realistic sample data using DML INSERT scripts.
    
3. *Optimized SQL Queries*

   * Wrote complex SQL queries for essential operations: ticket sales summaries, event attendance, revenue reporting, and seat availability.
   * Demonstrated JOINs, aggregation, subqueries, and window functions for advanced analytics.
    
4. *Sample Reports & Analytics*

   * Generate daily and monthly sales reports.
   * Identify top-selling events and customer purchase patterns.
   * Branch and venue-wise performance metrics.

## Project Files

- ERD_Relational_Normalisation.pdf      # ER diagram and normalization proofs (1NF → BCNF)
- DDL_Scripts.pdf                       # SQL scripts to create tables and constraints
- Insert_Queries.pdf                    # INSERT statements to populate sample data
- Queries.pdf                           # Collection of SELECT, JOIN, aggregation queries


## Database Design Philosophy

* *Clarity*: Schema clearly represents real-world event ticketing concepts.
* *Scalability*: Tables and indexes optimized for efficient query performance under large data volumes.
* *Maintainability*: Well-commented SQL scripts and modular design for easy updates and extensions.
* *Integrity*: Enforcement of referential integrity and business rules via constraints.
