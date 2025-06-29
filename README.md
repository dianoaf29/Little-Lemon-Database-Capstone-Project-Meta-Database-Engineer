# Project Objectives

This project aims to achieve the following objectives, focusing on database design, implementation, and interaction:

## 1. Database Infrastructure Establishment

- Configure and initialize the relational database management system.
- Set up and optimize the MySQL server environment.

## 2. Database Design and Implementation

- Design and implement a comprehensive Entity-Relationship (ER) diagram, ensuring data integrity and optimal relational structure.
- Populate database entities with relevant and accurate data.

## 3. Data Access and Efficiency Enhancements

- Create and implement a virtual table, `OrdersView`, to provide a simplified and aggregated view of order information.
- Develop a prepared statement, `GetMaxQuantity()`, designed to efficiently retrieve the maximum quantity, thereby promoting code reusability and reducing redundancy.
- Establish a prepared statement, `GetOrderDetail()`, aimed at minimizing query parsing time for retrieving detailed order information.

## 4. Database Procedural Development

- Implement a stored procedure, `CancelOrder()`, facilitating the deletion of order records based on a provided order ID.
- Create a stored procedure, `CheckBooking()`, to ascertain the booking status of restaurant tables.
- Develop a stored procedure, `AddValidBooking()`, for the validation and processing of new bookings, specifically declining reservations for tables already occupied.
- Establish a procedure, `UpdateBooking()`, to modify existing entries within the Booking table.
- Implement a new procedure, `CancelBooking()`, for the effective cancellation or removal of booking records.

## 5. Data Interactivity and Visualization

- Establish a Python environment for seamless connectivity and interaction with the database.
- Generate appropriate and insightful data visualizations to represent key findings and patterns within the dataset.


# Tools and Technologies

The successful execution of this project will leverage the following software and languages:

- **Tableau software**
- **MySQL / MySQL Workbench**
- **Python / Pandas / MySQL Connector**
- **Jupyter Notebook**

# Acquired Competencies

Through the completion of this project, the following key skills will be acquired:

- Proficiency in creating Entity-Relationship diagrams using MySQL Workbench.
- Competence in utilizing MySQL Workbench for forward engineering databases and tables, and populating data.
- Ability to perform Create, Read, Update, and Delete (CRUD) operations using both SQL and a Python client.
- Skill in accessing databases via the Python connector class.
- Expertise in creating comprehensive dashboards using Tableau software for business Key Performance Indicator (KPI) analysis.