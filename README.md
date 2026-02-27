# SQL

## Why Does SQL Even exist?

Imagine a company runs an application. For example, Amazon

Users:
- Sign up
- But products
- Cancel Subscriptions
- Click Buttons

All these actions generate DATA.

Now Amazon wants to answer questions like:
- How much revenue did we make this month?
- Which customers buy the most?
- Why are users leaving?

As of early 2026, Amazon has 150 Million active customers in India.
But the maximum number of rows Excel can store is 1,048,576 rows. So, technically, all this data cannot be stored in a Excel file.

We need a system to store this data, and this system is called a **Database.**

And the language used to talk to that database is: _SQL._

## What is a Database?
A database is:
_A system that stores structured data in tables._

Think of it like, very powerful Excel sheets, but optimized for:
- Billions of rows
- Fast searching
- Secure storage
- Multi-user access

## What is Structured Data?
Structured data is:
_Data that is orgaized in a fixed format - usually rows and columns._
It follows rules:

- Every row has the same type of information.
- Every column has a defined meaning.

For example, 
--------------------------------------------------------------------
|order_id    customer_id    price    order_date                 
--------------------------------------------------------------------
|1          |  101            800    |  2024-01-01                 |
--------------------------------------------------------------------
|2          |  102          |  25     |  2024-01-02                 |
---------------------------------------------------------------------
Here,
- order_id is always a number
- customer_id is always a number
- price is always a number
- order_date is always a date

Rules:
- Same columns for every row
- Same datatype per column
- Clean structure
- Predictable format

##### Why it is called "Structured"
Because it has:

- Defined schema (design)
- Fixed columns
- Consistent format
- Organized layout
The database knows exactly:
"What type of data belongs where."

#### What is Unstructured Date?

Unstructured data does not follow fixed rows or columns.
It has NO strict format.
For example:

In a Whatsapp chat, user could send or receive text, images, videos, emojis, etc.

Here, there are no fixed columns, no defined data types, no consistent format.

SQL is strongest with structured data.
For unstructured data, we use:

- text processing
- NLP
- AI Models

### What is SQL

SQL stands for:
_structured Query Language_

Structured --> works on structured data
Query --> means question
Language --> a way to communicate

So SQL is:
_A language to ask questions from structured data._

#### SELECT
Select is used to retrieve data from a table.

**Basic Syntax:**
_SELECT column_name
FROM table_name_

**Important**
Using _SELECT *_ is fine for learning.
but in real systems:

- it is inefficient
- It may pull unnecessary data.
- It increases processing time
Select only required columns.

### WHERE
Where filters the data.

**Why WHERE Exists**
Imagine SALES_DATA has 10 millions rows.
You don't want all rows.
You want:

- order from customer 101
- Orders in January
- Order where price > 500
  This is filtering.

  ### GROUP BY
  To answer How much did each customer spend?

  We must:
  - combine rows of same customer
  - Add their total spending
 
  **Important Rule**
  If you use GROUP BY:
  Every selected column must either
  - Be in GROUP BY
    OR
  - Be inside an aggregate function
 Otherwise --> SQL error.

### HAVING
WHERE filters rows before grouping.
HAVING filters groups after grouping.


### ORDER BY
ORDER BY controls how results are arranged.

### Execution ORDER
SELECT
FROM
WHERE
GROUP BY
HAVING
ORDER BY

### LIMIT
LIMIT restricts the number of rows returned.








