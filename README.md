# CMP 262 - Week 5, Lab 1
## Introduction to pandas and Exploratory Data Analysis

### What You Are Doing

In this lab, you will use pandas to explore a small Excel dataset of campus technology workshops. You will practice loading data, inspecting a DataFrame, selecting rows and columns, calculating summary statistics, creating a new column, sorting, and filtering.

You will complete your work in:

- `PandasIntro.ipynb`
- `AI-Use-Report.md`

Use the provided data file:

- `CampusWorkshopData.xlsx`

Keep the notebook and Excel file in the same folder.

### Learning Objectives

After completing this lab, you should be able to:

- import pandas with the standard alias
- load an Excel file into a DataFrame
- inspect rows, columns, shape, data types, and non-null values
- describe numerical and categorical data
- select columns and rows with brackets, `.loc[]`, and `.iloc[]`
- perform arithmetic on a column and add a new column
- sort and filter a DataFrame
- explain one useful finding from a dataset

### How to Complete the Lab

1. Open `PandasIntro.ipynb` in Visual Studio Code.
2. Make sure the notebook and `CampusWorkshopData.xlsx` are in the same folder.
3. Select a Python kernel.
4. Read each task carefully.
5. Write your own code in the code cell under each task.
6. Run each cell and check the output before continuing.
7. Complete the reflection and `AI-Use-Report.md`.

The notebook includes short examples using different data. The examples demonstrate the syntax but do not solve the assigned tasks.

## Dataset

The Excel file contains 12 fictional campus workshop records with these columns:

- `Workshop_ID`
- `Workshop`
- `Category`
- `Delivery_Mode`
- `Duration_Hours`
- `Registered`
- `Attended`
- `Satisfaction`

Some values are intentionally missing so you can observe how pandas reports non-null values.

## Lab Parts

### Part 1 - Load and Preview Data

Import pandas, load the Excel file, and use commands such as `head()`, `tail()`, `shape`, and `sample()`.

### Part 2 - Understand the DataFrame

Display column names, data types, and `info()`. Access one column and compare a pandas Series with a DataFrame.

### Part 3 - Summary Statistics

Calculate numerical statistics and examine unique categories and category counts.

### Part 4 - Select Rows and Columns

Select one or more columns. Then use `.loc[]` and `.iloc[]` to retrieve specified portions of the dataset.

### Part 5 - Arithmetic and a New Column

Create an `Attendance_Rate` column using the `Attended` and `Registered` columns.

### Part 6 - Sort and Filter

Sort workshops and create filtered subsets using comparison statements and Boolean masks.

### Part 7 - Final EDA Challenge

Answer a small research question using pandas output and explain one conclusion supported by the data.

## Before You Submit

Make sure:

- every task is completed
- every code cell has been run
- outputs are visible and there are no errors
- the reflection is complete
- `AI-Use-Report.md` is complete
- the Excel file remains in the repository

Then commit and push your work:

```text
git status
git add .
git commit -m "Complete Week 5 Lab 1"
git push
```

Open your GitHub repository and confirm that your latest work appears there.

### Important

Do not delete the questions, instructor comments, or provided files. GitHub Copilot may explain a concept, syntax, or error and may give a small unrelated example when asked, but it must not complete the assignment. You are responsible for writing, testing, and understanding your own work.
