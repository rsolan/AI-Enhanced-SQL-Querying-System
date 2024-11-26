# AI-Enhanced-SQL-Querying-System
Langchain, OpenAI GPT-3.5-turbo, SQLDatabaseToolkit, Flask framework

## Project Description: 

Developed a Flask-based web application that integrates AI-driven query handling with SQL databases using the Langchain framework. The system enables users to send natural language queries via an API endpoint, which are processed by an AI model (OpenAI's GPT-3.5) to retrieve data from a MySQL database. The application leverages the Langchain toolkit for SQL database interaction, providing an intelligent and flexible solution for querying complex database structures.

## Key Features:

Natural Language Query Processing: The system interprets user queries (e.g., “How many rows do we have in the cattle table?”) and converts them into SQL queries to retrieve accurate results from the database.

Dynamic Schema Discovery: Automatically identifies the structure of the database tables (e.g., table names, column names) and adapts queries accordingly.

Integration of LLMs: Uses OpenAI’s GPT-3.5-turbo model to process and interpret natural language queries for execution on a SQL database.

Visual Insights: Implements functionality to visualize database content and insights based on specific queries (e.g., providing data charts of specific tables).


## Toolstack:

Backend: Flask (Python Web Framework)

Database: MySQL, SQLAlchemy (for database ORM)

AI Integration: Langchain, OpenAI GPT-3.5-turbo, SQLDatabaseToolkit

Database Connectivity: pymysql

Environment Management: dotenv (for securely managing environment variables)


Designed and implemented the Flask web service that exposes a REST API endpoint for processing SQL queries.

Developed the ChatWithSql class for querying and interacting with the MySQL database using dynamic natural language queries.

Integrated Langchain agents and toolkits for seamless interaction with the database.

Configured OpenAI’s GPT model to interpret user queries and generate appropriate SQL commands.

Conducted extensive testing and troubleshooting of queries to ensure system reliability and accuracy.

Managed API key configuration and environmental setup through dotenv for secure API integration.
