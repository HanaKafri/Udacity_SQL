# SQL Analysis Project: Exploring the Sakila DVD Rental Database

This project involves exploring the **Sakila DVD Rental** database using SQL to gain insights into the customer base, movie rental patterns, payment details, and store performances. The project includes writing SQL queries to answer specific questions, generating visualizations based on the query results, and presenting the findings.

## Project Overview

The **Sakila Database** contains information about a company that rents movie DVDs. The analysis covers various aspects, such as movie rental trends, store performance comparisons, and customer payment behaviors. 

The project involves creating a slide presentation with four questions of interest, the SQL queries used to answer them, visualizations that display the output, and a brief summary for each question.

## Project Components

1. **Presentation Slides:** A slide deck consisting of four slides, each focusing on a different question of interest.
2. **SQL Queries Text File:** A text file containing all the SQL queries used to generate the visualizations and answer the questions.
   
### Slide Deck Details

Each slide in the presentation contains:

- A question of interest.
- The SQL query used to answer the question.
- A visualization (graph, chart, or table) created using the output of the SQL query.
- A brief summary based on the data and visualization.

## Questions Explored:

### 1. What is the Rental Count of Film Categories?
- **Objective:** Identify the rental count for family movie categories.
- **Query:** Lists each movie, its category, and the number of times it has been rented out.
- **Visualization:** A chart showing rental counts for different family movie categories.

### 2. How do the Two Stores Compare in Their Rental Orders on a Monthly Basis?
- **Objective:** Compare the monthly rental orders between the two stores.
- **Query:** Returns the store ID, year, month, and the count of rental orders for each store.
- **Visualization:** A chart comparing the number of rental orders fulfilled by each store every month.

### 3. Who Were Our Top 10 Paying Customers and What Were Their Monthly Payment Patterns in 2007?
- **Objective:** Determine the top 10 paying customers, their payment frequency, and total monthly payments in 2007.
- **Query:** Captures customer names, payment dates, and total payments made each month by these top customers.
- **Visualization:** A chart showing total monthly payments by each of the top 10 customers.

### 4. What is the Difference in Monthly Payments for Each of the Top 10 Paying Customers in 2007?
- **Objective:** Analyze the difference in monthly payments across months for the top 10 paying customers.
- **Query:** Compares the payment amounts in each successive month for these customers and identifies the customer with the most significant difference.
- **Visualization:** A graph illustrating monthly payment differences for each customer.

## SQL Concepts Utilized

- **JOINs and Aggregations:** All queries involve at least one JOIN operation and aggregation function to summarize data.
- **Subqueries and Common Table Expressions (CTEs):** At least two queries use subqueries or CTEs to break down complex operations.
- **Window Functions:** At least one query includes a window function, with its results included in the final visualization.


## Files Included

1. **queries.txt**: Contains SQL queries used to extract data for each question.
2. **report.pdf**: PDF file containing slides with questions, SQL queries, and visualizations.
