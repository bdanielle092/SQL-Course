# Installations

## PostgreSQL

### Installing PostgreSQL Server & pgAdmin 4

We will be using PostgreSQL throughout this course for your relational database management system. pgAdmin is the GUI application we will use to manage and interact with our databases. And psql is the interactive terminal for Postgres.

Follow the instructions at the appropriate links below to install PostgreSQL Server, pgAdmin and psql.

- [Mac OS](https://www.postgresqltutorial.com/install-postgresql-macos/)
- [Windows PC](https://www.postgresqltutorial.com/install-postgresql/)

#### Mac OS: Error on Database Restore

If you get `Failed (exit code: -6)` when you are trying to restore the dvdrental database, please download [the latest version of pgAdmin](https://www.pgadmin.org/download/pgadmin-4-macos/) and replace the current one in your Applications directory.

Make sure to restart any open pgAdmin windows.

## Connecting to your server & Loading a database

Once you are done with installations, continue the tutorial:

1. [Connect To a PostgreSQL Database Server](https://www.postgresqltutorial.com/connect-to-postgresql-database/)
1. [Load PostgreSQL Sample Database](https://www.postgresqltutorial.com/load-postgresql-sample-database/) In this part of the tutorial, scroll down until you get to the section called **Load the DVD Rental database using the pgAdmin**. This is where you should start.


#### Query Editor

Once you have restored the test database, you can see your tables by navigating into the `dvdrental > Schemas > Public > Tables`.

![Accessing the tables](./images/dvdrentals_tables.png)

Now you can try running a query!

Make sure your dvdrental db is selected. In the image below, **1** opens your query editor. Type in the following:

```sql
SELECT
   first_name,
   last_name,
   email
FROM
   customer;
```

Click the icon labeled **2** to run your SELECT statement and make sure you get back results.

![Query Editor](./images/run_select_query.png)

## Lucidchart

If you don't already have one, create a new Lucidchart account by going [here](https://app.lucidchart.com/users/registerLevel#/createAccount) and clicking the **Continue with Free** button.

## Google Account

If you do not have a Google email, please register for one [here](https://accounts.google.com/signup/v2/webcreateaccount?flowName=GlifWebSignIn&flowEntry=SignUp). This will be used primarily for utilizing Google Sheets.

## Github

Github is the primary site that software developers throughout the world use to store their code, and share it with other developers. Visit the [sign up page](https://github.com/join) and create your own, free account if you don't have one. We will be using this for class resources & curriculum.

