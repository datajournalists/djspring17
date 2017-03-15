### Homework data exercises (15%)

There are 10 individual homework data exercises. After the second assignment, the instructors will add here the assignment details. You will send your completed assignments via email.


## - Statistics exercise 1. Deadline: Wed. March 1, noon. Sent via email.

## - Statistics exercise 2. Deadline: Wed. March 8, noon. Sent via email.

## - SQL exercise 1. Deadline: Wed. March 15, noon.

Complete the exercises of [Part 1 of this SQLite tutorial](https://github.com/tthibo/SQL-Tutorial/blob/master/tutorial_files/part1.textile#creating-the-first-database).

Pick data from the data sets you are using for your story and import it to SQLite or create a SQL database following what you learned doing the Part 1 Tutorial exercise [(more help here)](https://www.w3schools.com/sql/sql_create_db.asp). Ask the data 3 questions using queries and the answers.

Send your instructors **via email**:

1. A short comment about what you learned by doing the Part 1 Tutorial exercise (and any doubts or problems you had).

2. The questions you asked the data and the answers you got (very brief)

Further help: [SQLite Wiki](https://github.com/lazierthanthou/sqlite-manager/wiki/Common-Tasks), [SQL Intro](https://www.w3schools.com/sql/sql_intro.asp)

## - SQL exercise 2. Deadline: Wed. March 22, noon.

**Find out who gives money to NY Rep. Christopher Collins [(profile in FEC)](https://beta.fec.gov/data/candidate/H8NY29032/?cycle=2016)**

Create a new database called `collins` (it will get the .sqlite added, so when you create it will be `collins.sqlite`).
Download [collins.zip](http://bit.ly/collinssqliteexcercise). It includes a data.csv file of individual contributors to New York Rep. House representative Chris Collins for period 2015-2016, and a .txt file with details of the database record layout. The source is [the FEC](https://beta.fec.gov/data/committee/C00520379/?tab=receipts&cycle=2016).

Import data.csv into Excel and review the headers and check what each one stands for in the .txt record layout. Create a new worksheet in Excel with the  following columns:
committee_id
report_year
report_type
entity_type
contributor_first_name
contributor_middle_name
contributor_last_name
contributor_city
contributor_state
contributor_occupation
contributor_zip
contribution_receipt_date
contribution_receipt_amount

Open the SQL `collins.sqlite` database and create a table called `contributors`.
Add the previous fields in SQLite. Define committe_id as INTEGER and primary key.
Define the ZIP and DATE fields as VARCHAR. The contribution_receipt_amount as INTEGER.

Once you’ve done that, write queries to do the following:
1. Show the contributors from Virginia
2. Show contributors from New York who gave at least $500.00
3. Count how many contributors are from New York and how much they gave in total
4. Count how many contributors are from each state and how much they gave per in total per state
5. Show contributors who listed their occupation as Retired, and order amounts from largest to smallest
6. Show contributors who listed their occupation as CEO, and order amounts from largest to smallest

Email us the `collins.sqlite` file as an attachment and the SQL results from 2 of your queries as .csv

- Statistics exercise 3. Deadline: Wed. March 29, noon
- Statistics exercise 4. Deadline: Wed. April 5, noon
- Cleaning and extracting data. Deadline: Wed. April 19, noon
- Documents extraction exercise.  Deadline: Wed. April 26, noon
- Create charts or a simple graph database or network graph visualization with data of your Story 2. Deadline: Wed. May 3, noon
- GeoSpatial Analysis Exercise. Deadline: Wed. May 10, noon
