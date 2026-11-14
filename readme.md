# Python to SQL Workshop

A practical, hands-on introduction to SQL for Python users, using SQLite and Jupyter notebooks.

## Overview

This workshop is designed to help Python users develop foundational SQL skills and understand how relational databases can be used to store, query, and analyse data.

It introduces SQL concepts progressively, drawing comparisons with familiar Python and pandas operations along the way. The aim is not just to learn SQL syntax, but to understand how SQL fits into a typical data analysis workflow.

The workshop uses **SQLite**, a lightweight database that runs locally and requires no separate database server.

## Learning objectives

By working through the notebook, you will learn how to:

- Understand relational databases, tables, rows, and columns.
- Retrieve data using `SELECT`.
- Filter and sort records using `WHERE`, `ORDER BY`, and `LIMIT`.
- Summarise data using aggregate functions such as `COUNT`, `SUM`, and `AVG`.
- Group records using `GROUP BY` and filter aggregated results using `HAVING`.
- Combine tables using `JOIN`.
- Use subqueries and Common Table Expressions (CTEs).
- Apply window functions for more advanced data analysis.
- Execute SQL queries from Python using `sqlite3`.
- Transfer query results into pandas DataFrames for further analysis.

## Requirements

You will need:

- [Anaconda or Miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
- Python 3.10 or later
- Git (optional, for cloning the repository)

SQLite and Python's `sqlite3` module are included with standard Python installations.

## Environment setup

It is recommended to use a dedicated Conda environment for this workshop.

**1. Clone the repository**

```bash
git clone https://github.com/samuel-shilling/python-to-sql-workshop.git
cd python-to-sql-workshop
```

**2. Create a Conda environment**

```bash
conda create -n python-to-sql python=3.12
```

**3. Activate the environment**

```bash
conda activate python-to-sql
```

**4. Install the required packages**

```bash
conda install pandas jupyter ipykernel
```

**5. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open the workshop notebook and make sure the `python-to-sql` kernel is selected.

To deactivate the environment when you have finished:

```bash
conda deactivate
```

## Workshop structure

The workshop is organised as a single, progressive Jupyter notebook, with explanations, worked examples, and exercises.

| Section | Topic |
|---|---|
| 1 | Introduction to relational databases and SQLite |
| 2 | Retrieving data with `SELECT` |
| 3 | Filtering, sorting, and limiting results |
| 4 | Aggregate functions and grouping |
| 5 | Joining multiple tables |
| 6 | Subqueries and CTEs |
| 7 | Window functions |
| 8 | Running SQL from Python |
| 9 | Integrating SQL with pandas |
| 10 | Practical exercises |

## Approach

The workshop uses a fictional business dataset to provide a consistent example throughout.

Each section introduces a new concept, demonstrates its use, and provides opportunities to practise. Where relevant, SQL queries are compared with equivalent pandas operations to make the transition from Python more intuitive.

## Future development

Potential extensions include:

- Additional exercises and solutions.
- More complex database examples.
- Query optimisation and indexing.
- Working with larger datasets.
- Connecting Python to external SQL databases such as PostgreSQL.

## Licence

This project is intended as an open learning resource. Feel free to use it for personal learning and educational purposes.