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

*Why it's called "Structured"*

Because it has:
- 







