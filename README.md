# Advanced Database - Data Warehouse & NoSQL Implementation

This repository contains the coursework for the Advanced Database (CIT6234) course, covering two main assignments:

1.  **Assignment 1: Data Warehouse Design and Implementation (DB2)**
2.  **Assignment 2: NoSQL Database Implementation (MongoDB)**

[cite_start]Both assignments are based on the **Airbnb Property Booking** case study. [cite: 37]

## Assignment 1: Data Warehouse (DB2)

This assignment focuses on the design and implementation of a data warehouse using IBM DB2. [cite_start]The objective was to create a data warehouse to assist long-term decision-making processes for the chosen case study. [cite: 3]

### Tasks Performed:

* [cite_start]**Conceptual Schema Design:** Designed the data warehouse conceptual schema using a [Star/Snowflake] schema, created with [Draw.io/other modeling tool]. [cite: 13, 14]
* [cite_start]**Data Dictionary:** Included a comprehensive data dictionary for the data warehouse. [cite: 17]
* [cite_start]**Fact Table Size & Storage Calculation:** Performed calculations for the fact table size and storage requirements within the database schema. [cite: 18]
* [cite_start]**Data Warehouse Implementation (DDL):** Implemented the data warehouse on IBM DB2 using SQL Data Definition Language (DDL) commands. [cite: 19, 20]
* [cite_start]**Sample Data Insertion (DML):** Populated the data warehouse with at least 10 sample records in each table using SQL Data Manipulation Language (DML) commands. [cite: 21, 22]
* [cite_start]**Procedural SQL Development:** Developed and demonstrated the following procedural SQLs: [cite: 23]
    * [cite_start]Stored Procedure [cite: 24]
    * [cite_start]Trigger [cite: 25]
    * [cite_start]User-Defined Function [cite: 26]
    * [cite_start]Demonstrated correct implementation/invocation/execution with screenshots. [cite: 27, 28]
* [cite_start]**Complex SQL Queries:** Constructed various complex SQL queries demonstrating: [cite: 29, 30, 31]
    * [cite_start]Joins of at least 3 tables. [cite: 32]
    * [cite_start]`GROUP BY` / `ROLLUP` / `CUBE` with `HAVING` clause. [cite: 33]
    * [cite_start]Views. [cite: 34]
    * [cite_start]Two additional SQL commands not covered in lectures. [cite: 35]

### Case Study:

* [cite_start]**CS 1: Data Warehouse for Airbnb Property Booking** [cite: 37]
    * [cite_start]This data warehouse is designed to analyze Airbnb property listings, bookings, customer demographics, seasonal pricing trends, and host performance. [cite: 38]

## Assignment 2: NoSQL Database (MongoDB)

[cite_start]This assignment builds upon Assignment 1's scenario, focusing on implementing a NoSQL database (MongoDB) for data storage and retrieval. [cite: 50, 51, 62, 63]

### [cite_start]Part A: MongoDB (65 Marks) [cite: 64]

* [cite_start]**Document-Based Data Modeling:** Constructed a document-based data modeling representation for the chosen case study in MongoDB. [cite: 65]
* [cite_start]**Data Dictionary (MongoDB):** Included a data dictionary for the MongoDB collections, detailing object names, data types, and unique constraints. [cite: 68]
* [cite_start]**Database & Collection Creation:** Created the MongoDB database and its respective collections. [cite: 71]
* [cite_start]**Sample Data Entry:** Entered at least 10 sample documents into each collection. [cite: 72]
* [cite_start]**NoSQL Queries:** Constructed various NoSQL queries demonstrating: [cite: 73, 74]
    * [cite_start]Logical operation (AND, OR, NOT). [cite: 75]
    * [cite_start]Comparison operator (greater than, greater than and equal, less than, etc.). [cite: 76]
    * [cite_start]Aggregate function (sum, average, max, min, count). [cite: 77]
    * [cite_start]One query with `project` command. [cite: 78]
    * [cite_start]One query with `size` clause. [cite: 79]
* [cite_start]**Update Operations:** Constructed NoSQL commands to update particular record(s) based on certain criteria. [cite: 80]
* [cite_start]**Delete Operations:** Constructed NoSQL commands to delete some specific records based on certain criteria. [cite: 81]
* [cite_start]**Additional NoSQL Commands:** Included any TWO NoSQL commands that are not covered in lecture. [cite: 82]

### [cite_start]Part B: Short Essay (35 Marks) [cite: 83] [cite_start]& Presentation (10 Marks) [cite: 48, 89]

* [cite_start]**Short Essay:** Wrote a short essay (maximum 400 words) on the impact of Big Data in any chosen industry/domain. [cite: 84, 85]
* [cite_start]**Presentation:** Delivered a presentation solely on Part B (the short essay) during Week 14. [cite: 55, 59]

## Getting Started

To run the code and explore the databases:

### Assignment 1 (DB2)

1.  **Install IBM DB2:** Ensure you have IBM DB2 installed and configured.
2.  **Import SQL Scripts:** Import the SQL DDL and DML scripts into your DB2 environment.
3.  **Execute Procedural SQLs:** Run the stored procedures, triggers, and user-defined functions as demonstrated in the assignment.

### Assignment 2 (MongoDB)

1.  **Install MongoDB:** Ensure you have MongoDB installed and running.
2.  **Import Data:** Use `mongoimport` or similar methods to import the sample data into your MongoDB instance, or run the provided scripts to create collections and insert data.
3.  **Run Queries:** Execute the NoSQL queries in a MongoDB shell or through a MongoDB client.
