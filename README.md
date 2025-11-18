Music Store SQL Analysis

A complete end-to-end SQL data analysis project using PostgreSQL and pgAdmin4.
This project explores an online music store’s database and answers key business questions through optimized SQL queries.

Project Overview

The goal of this project is to analyze sales, customer behavior, music preferences, and revenue patterns using relational database concepts.
All insights are derived purely through SQL — no external tools required.

The project includes:

Database schema interpretation
Data cleaning and exploration
Analytical SQL queries
Business insights and conclusions

Tools & Technologies

PostgreSQL 16
pgAdmin 4
SQL (DDL, DML, Joins, Aggregations, Window Functions)

Project Structure
Music-Store-Analysis/
│── dataset/                     # CSV files to create and populate tables
│── analysis.sql                 # All analytical SQL queries
│── music_store_db_backup/       # PostgreSQL backup (easy restore)
│── MusicDatabaseSchema.png      # Database schema diagram
│── README.md                    # Documentation

Database Schema

The music store database contains the following entities:
Customers
Invoices & Invoice Items
Tracks / Albums / Artists
Genres
Employees
Media Types
These tables are connected using primary–foreign key relationships.

How to Run This Project
1. Create a new PostgreSQL database
CREATE DATABASE music_store;

2. Restore the backup file (recommended)

pgAdmin → Right-click database → Restore → Select backup → Run

This loads:

✔ Tables
✔ Data
✔ Relationships

3. Run analytical queries

Open analysis.sql and execute queries to generate insights.

Key Questions Answered

Some of the business questions solved in this project:

Music Insights

What are the most popular genres?

Who are the top artists?

What are the best-selling tracks?

Sales & Revenue Analysis

Which countries generate the highest revenue?
What is the average order value?
Which customers purchase the most music?
Customer Geography
Which city has the highest spending?
Which country has the most customers?

