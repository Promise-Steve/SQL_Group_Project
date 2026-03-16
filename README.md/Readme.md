# Movie Rating Database (SQL Project)

## Project Overview

This project demonstrates how to design and explore a **Movie Rating Database** using **SQL (Structured Query Language)**.

The goal is to simulate a simple movie rating system where users rate movies. Using SQL queries, we explore user data, analyze ratings, and perform meaningful data retrieval operations.

The project focuses on practising **core database concepts and analytical SQL queries**, similar to tasks performed by data analysts when working with relational databases.

---

# Project Objectives

The objectives of this project are to:

* Design a relational database structure
* Create and manage tables using SQL
* Insert structured datasets into tables
* Query data using SQL statements
* Apply filtering and logical operators
* Sort and organise query results
* Perform basic data analysis on movie ratings

---

# Database Structure

The database **MovieRatingDB** consists of three relational tables:

### 1. Users Table

Stores information about users who rate movies.

Columns include:

* `User_Id`
* `Name`
* `Age`
* `Gender`
* `Location`

---

### 2. Movies Table

Stores movie details.

Columns include:

* `Movie_Id`
* `Title`
* `Release_Year`
* `Genre`
* `Director`

---

### 3. Ratings Table

Connects users and movies by storing ratings.

Columns include:

* `Rating_Id`
* `User_Id`
* `Movie_Id`
* `Rating_Value`
* `Rating_Date`

This table establishes the **relationship between users and movies**.

---

# Tools Used

The following tools were used in this project:

* **SQL (Structured Query Language)** – for database creation and data querying
* **MySQL / PostgreSQL / SQLite** – for running SQL queries
* **GitHub** – for project documentation and version control
* **CSV (Comma-Separated Values) datasets** – for storing and importing sample data

---

# Dataset

The dataset used in this project simulates a movie rating platform.

The repository includes datasets for:

* **Users**
* **Movies**
* **Ratings**

These datasets are located inside the:

```
dataset/
```

folder in the repository.

Example dataset file:

```
dataset/Users_Table.csv
```

The **Users dataset** contains information such as:

* User ID
* Name
* Age
* Gender
* Location

---

# Project Phases

## Phase 1: Database and Table Creation

In this phase:

* The database **MovieRatingDB** is created
* Tables for Users, Movies, and Ratings are created
* Table schemas are verified

---

## Phase 2: Data Insertion and Basic Queries

Sample data is inserted into the tables.

Basic queries are written to explore the data, such as:

* View all users
* List all movies
* View all ratings
* Find movies rated by a specific user

---

## Phase 3: Filtering and Logical Operations

SQL comparison and logical operators are used to analyse data.

Examples include:

* Find users older than 25
* Find movies released between 2000 and 2020
* Find female users from Abuja
* Find ratings greater than or equal to 4

---

## Phase 4: Sorting and Pagination

Data is organised and filtered using SQL commands.

Examples include:

* Sort movies by release year
* List distinct genres
* Retrieve the top 3 highest ratings
* Skip rows using OFFSET
* Sort users alphabetically

---

# Project Screenshots
<img width="1225" height="790" alt="Users_from_Abuja_who are females" src="https://github.com/user-attachments/assets/891253be-9412-448e-b0f0-0137cfabd05f" />

<img width="1148" height="805" alt="view_all_ratings" src="https://github.com/user-attachments/assets/881b9ccc-641e-46ca-874a-6e704006c3de" />

<img width="1236" height="815" alt="New<img width="1216" height="794" alt="ratings_greater than or equal to 4" src="https://github.com/user-attachments/assets/abaaa80a-fb92-4ce3-b121-36e5368bc37b" />
est_release" src="https://github.com/user-attachments/assets/1e8b241e-2ee9-4f64-a83f-8791691cb3ad" />
<img width="1239" height="791" alt="users_older_than_25 years" src="https://github.com/user-attachments/assets/0b297e6c-e508-4fef-8b00-01491753be69" />


<img width="1143" height="798" alt="movies_released_between_2000   2022" src="https://github.com/user-attachments/assets/f9171984-1bf9-4400-b736-9044ab3808be" />


---<img width="1222" height="826" alt="Distinct_genres" src="https://github.com/user-attachments/assets/6536386c-b86d-4dac-a092-9d2911bb6e55" />


# Repository Structure

```
movie-rating-database-sql-project
│
├── README.md
│
├── dataset
│   └── Users_Table.csv
│
├── sql
│   ├── create_database.sql
│   ├── create_tables.sql
│   └── queries.sql
│
├── screenshots
│   ├── database_creation.png
│   ├── tables_created.png
│   ├── query_results.png
│
└── project_documentation
    └── Movie_Rating_Database_Project.docx
```

---

# How to Run the Project

1. Clone the repository
2. Open your SQL environment (MySQL, PostgreSQL, SQLite, etc.)
3. Create the database `MovieRatingDB`
4. Run the SQL scripts to create tables
5. Import datasets from the `dataset` folder
6. Execute the queries provided in the SQL files

---

# Conclusion

This project demonstrates how SQL can be used to build and analyse a relational database system. By working through the different phases of the project, key database concepts such as table creation, data insertion, filtering, sorting, and logical query building were explored.

The project reflects real-world tasks performed by data analysts when working with structured datasets.

---

# License

This project is intended for **educational and learning purposes**.
