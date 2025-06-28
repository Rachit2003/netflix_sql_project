# 🎬 Netflix SQL Data Analysis Project

This project performs **end-to-end SQL-based analysis** on Netflix's content catalog to solve 15 business and analytical problems. It showcases practical SQL skills including window functions, date operations, text search, filtering, and aggregation.

---

## 🧰 Tools & Technologies

- SQL (PostgreSQL syntax)
- PostgreSQL functions: `RANK()`, `UNNEST`, `SPLIT_PART`, `TO_DATE`, `EXTRACT`
- Data Types: `VARCHAR`, `NUMERIC`, `INT`, `DATE`, `ARRAY`
- Data Source: [Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 📊 Executed Queries & Business Questions

### 1️⃣ Count of Movies vs TV Shows  
Identify how many content items are movies and how many are TV shows.

### 2️⃣ Most Common Rating by Type  
Use `RANK()` to find the most frequent content rating for both Movies and TV Shows.

### 3️⃣ Movies Released in 2020  
Filter all movies released in the year 2020.

### 4️⃣ Top 5 Countries with Most Content  
Use `UNNEST` to split multi-country entries and find which countries have the most Netflix content.

### 5️⃣ Longest Movie  
Identify the movie with the maximum duration.

### 6️⃣ Content Added in Last 5 Years  
Find content where `date_added` is within the last 5 years from the current date.

### 7️⃣ All Content by Director 'Rajiv Chilaka'  
Use pattern matching to find movies/TV shows directed by Rajiv Chilaka.

### 8️⃣ TV Shows with More Than 5 Seasons  
Use `SPLIT_PART()` and numeric conversion to find long-running shows.

### 9️⃣ Count Content by Genre  
Use `UNNEST` on the `listed_in` field to count how many shows belong to each genre.

### 🔟 Average Yearly Content Added in India  
Use `TO_DATE()` and `EXTRACT()` to calculate yearly averages for content added in India, and return top 5 years.

### 1️⃣1️⃣ List All Documentaries  
Find content where the genre includes "Documentaries".

### 1️⃣2️⃣ Content Without a Director  
Find records where the `director` field is `NULL`.

### 1️⃣3️⃣ Salman Khan Movies in Last 10 Years  
Filter content featuring Salman Khan, added within the last 10 years.

### 1️⃣4️⃣ Top 10 Actors in Indian Movies  
Use `UNNEST` to split `casts` and find top actors in Indian-produced content.

### 1️⃣5️⃣ Categorize Content as "Good" or "Bad"  
Label content as "BAD CONTENT" if the description includes "kill" or "violence", otherwise "GOOD CONTENT".

---


## 📂 How to Run

1. Load the Netflix dataset into your SQL database.
2. Execute the `CREATE TABLE` and `COPY` statements (with `CSV HEADER`).
3. Run each SQL block to explore the answers.

---

## 🏷️ Tags

#SQL #Netflix #DataAnalytics #PostgreSQL #PortfolioProject #EDA #BusinessIntelligence
