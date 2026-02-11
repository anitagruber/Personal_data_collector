# Personal_data_collector
Production-ready data collection system with relational database design, authentication, admin dashboard and analytics visualization.

# Personal Data Collector App

A full-stack web application built with Streamlit and PostgreSQL.

## Project Goal

The goal of the project was to design and implement a relational database-backed data collection system.  
The application allows users to:

- Submit personal information
- Store address, education, and employment data
- Save records into a PostgreSQL database
- Display stored data in a structured table view

## Features Implemented

- Multi-section data entry form (Personal, Address, Education, Employment)
- Relational database design with foreign keys
- Separate data access layer (database.py)
- Secure connection using Streamlit Secrets
- Cloud database (Neon)
- Deployed on Streamlit Cloud

## Database Design

The database consists of four related tables:

- personal
- address
- education
- employment

Relationships are implemented using primary and foreign keys.

## Technologies Used

- Python
- Streamlit
- Matplotlib
- PostgreSQL
- Neon (Cloud database)
- psycopg2
- GitHub

## Live Application

[Open Streamlit App](https://personal-data-collector-anita.streamlit.app)

## Author

Anita Gruber, Zoltán Nagy
