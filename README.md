# Pandas Practice Tasks

## Level 1: Basic
**Goal:** Learn to read, explore, and manipulate data

- Create a DataFrame of students with columns: `name`, `age`, `marks`.
- Print the first 5 rows.
- Print only `name` and `marks`.
- Filter students with `marks > 80`.
- Load a CSV file (or create dummy data). Example: `sales.csv` with `product`, `quantity`, `price`.
- Find total sales for each product.
- Add a new column `total = quantity * price`.
- Sort products by total sales.
- Create a Series with temperatures `[30, 32, 28, 25, 27]` for 5 days.
- Convert temperatures from Celsius → Fahrenheit.
- Find max, min, mean temperatures.

---

## Level 2: Intermediate (Data Cleaning & Analysis)
**Goal:** Work with missing values, grouping, and aggregations

- Create a DataFrame `employees.csv` with `id`, `name`, `department`, `salary`.
- Fill missing salaries with the average salary.
- Find highest paid employee.
- Group by `department` and calculate average salary.
- Use the Titanic dataset: `sns.load_dataset("titanic")`
  - Find how many passengers survived.
  - Show average age by class (`pclass`).
  - Find survival rate by gender (`sex`).
- From a dataset of marks (`name`, `subject`, `marks`):
  - Find average marks per student.
  - Find the student with highest total marks.

---

## Level 3: Advanced (Realistic Projects)
**Goal:** Combine multiple datasets, analyze trends

### E-commerce Orders
**Dataset:** `orders.csv` with `order_id`, `customer`, `product`, `quantity`, `price`, `date`

**Tasks:**
- Find total revenue.
- Find the top 5 customers by spending.
- Find sales per month.
- Which product has maximum sales?

### Bank Transactions
**Dataset:** `transactions.csv` with `id`, `account_no`, `type` (debit/credit), `amount`, `date`

**Tasks:**
- Find total credits & debits per account.
- Detect negative balance accounts.
- Find top 3 highest transactions.

### COVID-19 Dataset
**Dataset:** Downloadable from Kaggle or use dummy data  
**Columns:** `date`, `country`, `cases`, `deaths`, `recovered`

**Tasks:**
- Plot total cases per country.
- Find country with highest recovery rate.
- Show trend of cases over time for top 3 countries.

---

## Level 4: Mini Project (Capstone)
**Combine everything you learned**

### Project: Movie Ratings Analysis
**Dataset:** `movies.csv` with `movie`, `genre`, `rating`, `votes`, `revenue`

**Tasks:**
- Clean missing values (fill average ratings, drop missing revenue)
- Find top 10 movies by rating.
- Find average rating per genre.
- Find which genre earns the most revenue.
- **Bonus:** Plot rating vs revenue using Matplotlib/Seaborn.
