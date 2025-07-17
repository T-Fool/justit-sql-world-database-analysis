# World Database Analysis – SQL Project

## 🎯 What I Built
For my Week 3 project at the justIT Data Skills Bootcamp, I analyzed the 'world' database using SQL. I wrote a series of queries to answer specific questions, demonstrating my ability to filter, join, and rank data to extract meaningful information from a relational database.

## 💡 Key Things I Learnt
- **Filtering with `WHERE`**: I learned to use the `WHERE` clause to filter data based on specific criteria, such as a region or country code.
- **Combining Conditions with `AND`**: I practiced using the `AND` operator to create more specific queries that satisfy multiple conditions at once.
- **Joining Tables with `JOIN`**: This was a key lesson. I learned how to use `JOIN` to combine rows from two different tables (`country` and `countrylanguage`) based on a related column (`CountryCode`).
- **Sorting and Limiting with `ORDER BY` and `LIMIT`**: I learned how to rank data using `ORDER BY` (in descending order) and then use `LIMIT` to select only the top results, which is essential for "Top N" analysis.

---

## 🔍 SQL Queries & Insights

Below are the specific questions from my workbook and the SQL queries I wrote to answer them.

### 1. What are the countries in the Caribbean?
This query selects all countries from the `country` table that are located in the 'Caribbean' region. (SQL query and its result, listing Caribbean countries)
<img width="1122" height="587" alt="query-caribbean-countries" src="https://github.com/user-attachments/assets/6b4fbb7f-6fd2-4637-8556-900720325f9e" />

### 2. What are the cities in the UK with a population over 1 million?
This query filters the `city` table for records with the CountryCode 'GBR' and a population greater than 1,000,000. (SQL query and its result, listing large UK cities)
<img width="1121" height="585" alt="query-large-uk-cities" src="https://github.com/user-attachments/assets/277d0569-d7f2-48c2-91fd-493d215fbbe5" />

### 3. What is the official language of each country?
This query joins the `country` and `countrylanguage` tables to match countries with their official languages. (SQL query and its result, showing countries and their official languages)
<img width="952" height="596" alt="query-official-languages" src="https://github.com/user-attachments/assets/0014f31a-0fe7-4b49-b005-3d24dcaaa54d" />

### 4. What are the 5 most populated countries in the world?
This query sorts all countries by population in descending order and returns only the top 5. (SQL query and its result, showing the top 5 most populated countries)
<img width="1280" height="761" alt="World_DB" src="https://github.com/user-attachments/assets/3f951f1e-63e9-406b-8a18-e38f3e0f2d90" />

---

## 🛠️ SQL Skills Demonstrated
- `SELECT`, `FROM`, `WHERE`
- `JOIN ... ON` for combining tables
- `ORDER BY` with `DESC` for sorting
- `LIMIT` for ranking
- `AND` for multiple conditions
- Using aliases (`AS`) for clarity

## 🚀 How to Explore
1.  Download the `world db.sql` file.
2.  Import it into a MySQL database to create and populate the tables.
3.  Run any of the queries from this README to get the same results.

## 📁 Project Files
- `world db.sql` - The SQL file to set up the database.
- `screenshots/` - The Pictures containing the result of each query.
- `README.md` - This guide.

## 🎓 Part of My Bootcamp Journey

## 🤔 If I Had More Time
- I would use aggregate functions like `COUNT()` and `GROUP BY` to find the number of countries on each continent.
- I would write a more complex query to find the total population of all cities listed for each country.

---
*Week 3 of 8 – justIT Data Skills Bootcamp*
