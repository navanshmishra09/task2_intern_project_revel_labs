# task2_intern_project_revel_labs
### 📄 Description
This project automates the process of generating and executing SQL queries from natural language prompts using a transaction dataset. It leverages Google's Gemini Generative AI to translate user inputs into valid SQL queries and executes them on a dynamically created SQLite database using Python.

### ✨ Key Features
✅ CSV Data Ingestion: Automatically loads and processes the transaction_data.csv file using Pandas.

✅ Schema Inspection: Dynamically identifies the column names of the dataset to ensure accurate SQL generation.

✅ Natural Language to SQL: Translates natural language questions into valid SQL queries using Gemini AI.

✅ SQL Execution Engine: Runs the generated SQL queries against the transaction data in a SQLite in-memory database.

✅ Smart Error Handling: Automatically detects and corrects common SQL generation issues like incorrect column names.

✅ Interactive Prompting: Users can type queries in plain English and get real-time results.

### 🛠️ Technologies Used
Python

Pandas

SQLite3

Google Generative AI API (Gemini)

Regex (re) – for cleaning and parsing queries
### ⚙️ Setup Instructions
1. Clone the Repository
git clone https://github.com/navanshmishra9/task2_intern_project_revel_labs.git
2. Install Dependencies
pip install pandas google-generativeai 
3. Add Your Gemini API Key
Create a .env file in the project root directory and insert your API key:
API_KEY=****************
