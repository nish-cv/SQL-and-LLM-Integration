# SQL Query Generation using LangChain

This project involves a Python application that generates SQL queries using a language model from LangChain and executes them on a MySQL database.

## Project Description

The goal of this project is to demonstrate how to use a language model to generate and execute SQL queries based on natural language questions. The model uses the LangChain library to interpret the questions and create appropriate SQL queries. The database schema includes tables for countries, departments, employees, jobs, job history, locations, and regions.

## Installation

To get started, you need to install the following Python libraries. You can install them using `pip`:

```bash
pip install langchain
pip install langchain-community
pip install transformers
pip install SQLAlchemy
 pip install pymysql   
pip install dotenv # To store env variables (Optional)
```

## MySQL Server Setup

You will need a MySQL server setup and running to use this project. If you don't have MySQL installed, you can download and install it from the [MySQL website](https://dev.mysql.com/downloads/mysql/). Ensure your MySQL server is configured and running properly before attempting to connect to it from the application.

## Database

The database used in this project is a sample database obtained from [SQL Tutorial](https://www.sqltutorial.org/sql-sample-database/). This sample database consists of multiple tables including countries, departments, employees, jobs, job history, locations, and regions. Once you have installed MySQL and inserted the tables, use your user ID and passcode to create the `SQLDatabase` object.

## Authentication 

### Hugging Face

To use the Hugging Face model, you need to authenticate. You can obtain the `hf_auth` code by requesting it from the [Hugging Face website](https://huggingface.co/).

1. Go to the [Hugging Face website](https://huggingface.co/).
2. Sign up or log in to your account.
3. Navigate to your account settings to create a new API token.

## Usage

Once you have installed the necessary libraries and configured your API keys, you can run the application as shown in the notebook. Make sure to replace the placeholder values for `hf_auth` and `api_key` with your actual credentials.

## Contributing

If you would like to contribute to this project, please feel free to fork the repository and submit a pull request. 
