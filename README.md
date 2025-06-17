# NATURAL-LANGUAGE-TO-SQL-APP-VIA-GEMINI-PRO
This is an end-to-end Streamlit app that converts English questions into SQL queries using Google Gemini Pro (LLM) and runs them on a SQLite3 student database.

Features
Converts English (natural language) questions into SQL queries.
Powered by Gemini Pro LLM for intelligent text-to-SQL conversion.
Uses SQLite3 as the backend database.
Displays SQL results in an easy-to-read format.
How It Works
The user asks a question like: "Show me all students in Data Science class"

The app sends the question and a prompt to Gemini Pro.

Gemini returns the SQL query:

SELECT * FROM STUDENT WHERE CLASS = "Data Science";


The app runs the query on the SQLite database and displays the result.
