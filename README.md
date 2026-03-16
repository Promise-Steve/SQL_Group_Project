# Movie Rating Database (SQL Project)

## Project Overview

This project demonstrates how to design and explore a **Movie Rating Database** using **SQL (Structured Query Language)**.

The goal is to simulate a simple movie rating system where users rate movies. Using SQL queries, we explore user data, analyze ratings, and perform meaningful data retrieval operations.

The project focuses on practicing **core database concepts and analytical SQL queries**, similar to tasks performed by data analysts when working with relational databases.

---

# Project Objectives

The objectives of this project are to:

* Design a relational database structure
* Create and manage tables using SQL
* Insert structured datasets into tables
* Query data using SQL statements
* Apply filtering and logical operators
* Sort and organize query results
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
 <img width="1244" height="822" alt="View_all_users" src="https://github.com/user-attachments/assets/6d25dc9d-5c09-4cf7-be94-14fa0ad325a9" />


* View all ratings
  <img width="1148" height="805" alt="view_all_ratings" src="https://github.com/user-attachments/assets/b5d92bc8-f4ff-4eab-a142-623ae7890bf5" />


* Find movies rated by a specific user
  <img width="1160" height="785" alt="movies_rated_by_specific_users" src="https://github.com/user-attachments/assets/db8ad9c3-5ee0-49bc-a49c-93dff9fc7ce3" />


---

## Phase 3: Filtering and Logical Operations

SQL comparison and logical operators are used to analyse data.

Examples include:

* Find users older than 25
  <img width="1239" height="791" alt="users_older_than_25 years" src="https://github.com/user-attachments/assets/71ffdff9-4f03-4d21-8e9e-50b88dc14035" />

* Find movies released between 2000 and 2020
  <img width="1143" height="798" alt="movies_released_between_2000   2022" src="https://github.com/user-attachments/assets/9bc38c7d-19f3-4d47-bad6-86eca9293fde" />

* Find female users from Abuja
  <img width="1225" height="790" alt="Users_from_Abuja_who are females" src="https://github.com/user-attachments/assets/381175a0-2046-471c-8481-40740f5726d7" />

* Find ratings greater than or equal to 4
  
<img width="1216" height="794" alt="ratings_greater than or equal to 4" src="https://github.com/user-attachments/assets/598857c6-647f-4edc-8018-b7447f2c6f5c" />

---

## Phase 4: Sorting and Pagination

Data is organized and filtered using SQL commands.

Examples include:

* Sort movies by release year
  <img width="1236" height="815" alt="Newest_release" src="https://github.com/user-attachments/assets/c00c45b3-5423-45dc-a334-e693baf7772a" />

* List distinct genres
  <img width="1222" height="826" alt="Distinct_genres" src="https://github.com/user-attachments/assets/43af8e2b-c3ad-4d84-b7be-8951f2eabc88" />

* Retrieve the top 3 highest ratings
  <img width="1213" height="835" alt="Top 3_ Highest Rating" src="https://github.com/user-attachments/assets/1e6da383-64f2-42aa-9e4a-b1b267625d72" />

* Skip rows using OFFSET
  <img width="1163" height="799" alt="Offset_First 3 rows" src="https://github.com/user-attachments/assets/10843949-e95f-49e7-af1d-a86b3d759a77" />

* Sort users alphabetically
  <img width="1252" height="849" alt="Alphabetical sorting" src="https://github.com/user-attachments/assets/68b5b607-7561-4b8f-8c72-fc7cc2a17240" />



---

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

This project demonstrates how SQL can be used to build and analyze a relational database system. By working through the different phases of the project, key database concepts such as table creation, data insertion, filtering, sorting, and logical query building were explored.

The project reflects real-world tasks performed by data analysts when working with structured datasets.

---

# License

This project is intended for **educational and learning purposes**.
