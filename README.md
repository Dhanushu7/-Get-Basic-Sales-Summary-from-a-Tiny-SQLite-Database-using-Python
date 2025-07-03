# Sales Summary Using SQLite and Python

## Project Overview

This project demonstrates how to connect to a small SQLite database using Python, run SQL queries to extract sales insights, and visualize the results using bar charts. The script is designed for beginners to understand the integration of SQL with Python and basic data visualization techniques using Matplotlib and Pandas.

## Objectives

- Connect to an SQLite database using Python
- Create and populate a simple `sales` table with mock data
- Run basic SQL queries to extract business metrics
- Use Pandas to load query results and display summaries
- Visualize outputs with bar charts using Matplotlib

## Tools and Technologies

- Python (3.x)
- SQLite (via built-in `sqlite3` module)
- Pandas
- Matplotlib

## Dataset

The dataset is created within the script itself and includes mock sales records with the following fields:

- `product` (e.g., Product A, Product B, etc.)
- `quantity` (units sold)
- `price` (price per unit)
- `date` (date of sale)

## SQL Queries Executed

1. **Total quantity and revenue per product**
2. **Daily total revenue**
3. **Total units sold per product**
4. **Average price per product**
5. **Revenue per product on a specific date (2025-07-04)**

## Output

The script prints the output of each SQL query to the console and generates five bar charts:

- `chart1_revenue_by_product.png`
- `chart2_revenue_by_date.png`
- `chart3_units_sold.png`
- `chart4_avg_price.png`
- `chart5_revenue_2025_07_04.png`

Each chart is saved in the same directory for reporting or presentation purposes.

## How to Run

1. Make sure you have Python 3 installed on your system.
2. Install required Python libraries if not already installed:
   ```bash
   pip install pandas matplotlib
   ```
3. Run the script:
   ```bash
   python sales_summary.py
   ```

This will generate the SQLite database (`sales_data.db`), insert mock data, run SQL queries, and output the printed results and charts.

## File Structure

| File/Folder                          | Description                                        |
|-------------------------------------|----------------------------------------------------|
| `sales_summary.py`                  | Main Python script to create DB, run queries, and plot charts |
| `sales_data.db`                     | SQLite database file (created on first run)        |
| `chart1_revenue_by_product.png`     | Bar chart showing revenue by product              |
| `chart2_revenue_by_date.png`        | Bar chart showing daily revenue                   |
| `chart3_units_sold.png`             | Bar chart showing units sold per product          |
| `chart4_avg_price.png`              | Bar chart showing average price per product       |
| `chart5_revenue_2025_07_04.png`     | Bar chart showing revenue per product on a specific date |

## Author

**Dhanushu V**  
Email: dhanushu77@gmail.com  
GitHub: [your-github-username] (update with your actual username)
