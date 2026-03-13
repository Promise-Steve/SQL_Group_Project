# Movie Rating Database (SQL Project)

## Project Overview

This project demonstrates how to build and analyze a **Movie Rating Database** using SQL. The system simulates a simple movie rating platform where users rate movies, allowing analysts to explore trends, user behavior, and movie popularity.

The project walks through key SQL concepts including:

* Database creation
* Table design
* Data insertion
* Data filtering
* Sorting and querying datasets

It is designed as a **hands-on SQL learning project** for beginners and aspiring data analysts.

---

# Database Name

`MovieRatingDB`

---

# Dataset

The project uses sample datasets representing **users, movies, and ratings**.

Currently included:

### Users Table Dataset

The `Users_Table.csv` file contains **371 user records** with the following fields:

| Column   | Description             |
| -------- | ----------------------- |
| User_Id  | Unique ID for each user |
| Name     | Name of the user        |
| Age      | Age of the user         |
| Gender   | Gender of the user      |
| Location | User's city             |

Example record:

| User_Id | Name         | Age | Gender | Location |
| ------- | ------------ | --- | ------ | -------- |
| 1       | Ade Taiwo    | 28  | Male   | Lagos    |
| 2       | Mary Johnson | 34  | Female | Abuja    |

---

# Database Structure

The database consists of **three relational tables**.

## 1. Users Table

Stores information about users who rate movies.

Columns:

* `User_Id`
* `Name`
* `Age`
* `Gender`
* `Location`

---

## 2. Movies Table

Stores movie information.

Columns may include:

* `Movie_Id`
* `Title`
* `Release_Year`
* `Genre`
* `Director`

---

## 3. Ratings Table

Connects users with movies and stores ratings.

Columns may include:

* `Rating_Id`
* `User_Id`
* `Movie_Id`
* `Rating_Value`
* `Rating_Date`

This table creates the **relationship between users and movies**.

---

# Project Phases

## Phase 1: Database and Table Setup

Create the database and tables.

Tasks include:

* Creating the `MovieRatingDB` database
* Creating the `Users`, `Movies`, and `Ratings` tables
* Verifying table schema

---

## Phase 2: Insert and Explore Data

Insert sample records and perform basic queries.

Example queries:

* View all users
* List all movies
* View all ratings
* Find movies rated by a specific user

---

## Phase 3: Comparison and Logical Operators

Practice filtering data using conditions.

Examples:

* Find users older than 25
* Find movies released between 2000 and 2020
* Find female users from Abuja
* Find movies that are not Sci-Fi
* Find ratings greater than or equal to 4

---

## Phase 4: Sorting and Pagination

Practice organizing query results.

Examples:

* Sort movies by release year
* List distinct genres
* Display top 3 highest ratings
* Skip rows using OFFSET
* Sort users alphabetically

---

# Skills Practiced

This project strengthens the following SQL skills:

* Database design
* Table creation
* Data insertion
* Query writing
* Filtering datasets
* Logical operations
* Sorting and pagination
* Data analysis using SQL

---

# How to Use This Project

1. Download the repository.
2. Import the dataset files.
3. Create the database `MovieRatingDB`.
4. Create the tables using SQL scripts.
5. Run queries to explore the dataset.

---

# Tools

This project can be run on:

* MySQL
* PostgreSQL
* SQLite
* Microsoft SQL Server

---

# Purpose

This project is designed for:

* SQL beginners
* Data analysis learners
* Database practice
* Portfolio projects for aspiring data analysts

---

# License

This project is intended for **learning and educational purposes**.
