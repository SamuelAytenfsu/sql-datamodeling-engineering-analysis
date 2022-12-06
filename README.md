#     style="text-align: center;"                                                 SQL-datamodeling-engineering-analysis


# Data Modeling, Data Engineering, Data Analysis
![Screenshot 2022-12-06 103648](https://user-images.githubusercontent.com/97622118/205955870-778408de-38c5-46d2-9dcc-260c00a34507.png)
## About
This project is divided into three parts: data modeling, data engineering, and data analysis. For all this part we used Pewlett Hackard (a fictional company) file and included in "Data" folder.
# Objective of the project
## The main objective of this project is to do a research about people whom the company employed during the 1980s and 1990s.
## The specific objective of the project is
 * To design the tables to hold the data from the CSV files.
 * To import the CSV files into a SQL database.
 * To answer questions about the data.

## Data Modeling
In this step I inspect the CSV files, and then sketch an Entity Relationship Diagram of the tables. To create the sketch, I used a tool like QuickDBD.
![Screenshot 2022-12-05 213834](https://user-images.githubusercontent.com/97622118/205948767-e63b0cb2-485c-4715-a35f-0bc9cc0b8260.png)
* Entity Relationship Diagram is included or table schemas provided for all tables 
## Data Engineering
I use the provided information to create a table schema for each of the six CSV files. First I specify the data types, primary keys, foreign keys, and other constraints.For the primary keys, I verify that the column is unique. Otherwise, create a composite key, which takes two primary keys to uniquely identify a row.
### Remeber: Be sure to create the tables in the correct order to handle the foreign keys.
After that import each CSV file into its corresponding SQL table.mTo avoid errors, import the data in the same order as the corresponding tables got created. And, remember to account for the headers when doing the imports.

   * All required columns are defined for each table 
   * Columns are set to the correct data type 
   * Primary Keys set for each table 
   * Correctly references related tables 
   * Tables are correctly related using Foreign Keys 
   * Correctly uses NOT NULL condition on necessary columns 
   * Accurately defines value length for columns 
## Data Analysis
In this section the following exploratory analysis were conducted on the imported data set:
  * List the employee number, last name, first name, sex, and salary of each employee.
  * List the first name, last name, and hire date for the employees who were hired in 1986.
  * List the manager of each department along with their department number, department name, employee number, last name, and first name.
  * List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
  * List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
  * List each employee in the Sales department, including their employee number, last name, and first name.
  * List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
  * List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
