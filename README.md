**Python Charmers Playground 🐍**
Welcome to Python Charmers! This repository is a curated collection of Python exercises, mini-projects, and data manipulation workflows designed to build and demonstrate proficiency in Python programming.

The content ranges from native Python data structures to API integrations and data analysis using the Pandas library.

**🎯 Repository Goals**
Skill Building: Practice and solidify core Python concepts including loops, conditionals, list comprehensions, and dictionary operations.

Data Manipulation: Master data extraction, transformation, and loading (ETL) utilizing both native Python lists and pandas DataFrames.

API Integration: Successfully call, parse, and handle JSON data from external REST APIs (e.g., RandomUser API, Met Office DataPoint).

Error Handling: Build robust scripts that include try-except blocks and logical fallbacks for missing or nested API data.

**📂 Project Structure**
notebook_tasks/ — Jupyter Notebooks containing structured lessons and exercises.

**Data Structures & Loops:** Exercises focusing on extracting and modifying nested list/dictionary data.

**API Calls & JSON Parsing:** Mini-projects demonstrating how to request data from web APIs and parse complex JSON trees.

**Pandas Fundamentals:** Tasks showing how to clean, filter, and structure raw data into Pandas DataFrames for analysis.

**🛠️ Tech Stack & Libraries**
Python 3.x

Pandas (import pandas as pd) - For structured data analysis and DataFrame manipulation.

Requests (import requests) - For sending HTTP requests to REST APIs.

JSON (import json) - For parsing API responses.

**🚀 Highlighted Mini-Projects**
**1. Fake User Generator (RandomUser API)**
A script that generates bulk fake user data by calling the RandomUser API, parsing the attributes (name, gender, location, DOB), and structuring the output into a clean Pandas DataFrame using both standard loops and dictionary comprehension.

**2. Weather Observations (Met Office API)**
A robust script that requests hourly weather observation data for specific coordinates in the Shetlands. It navigates highly nested JSON structures and features a while loop fallback system to automatically test backup weather stations if the primary API call returns empty data.

**3. Bookstore Inventory (Native Python vs. Pandas)**
An exercise demonstrating the difference between modifying datasets using standard Python list comprehensions and doing the same operations using vectorized Pandas functions.
