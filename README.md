# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) SQL Basics

#### Where In The World Is Carmen Sandiego?

We're going to use what we've already learned about searching with SQL commands and apply it to chase down and capture an elusive and world-renowned thief: Carmen Sandiego. Follow the clues, use the interweb, write down both the SQL commands/queries you used and your answers to the clues, and figure out where Carmen is headed so we can catch her.

## Exercise

#### Requirements

- Fork and clone this repo.
- Go inside the folder you just cloned
- Use the `find_carmen.sql` file as your "answer sheet."
- From the command line, let's create a new database called `carmen` and populate it with the SQL found in `world.sql`.

```sh
# Enter psql
psql

# Create database
CREATE DATABASE carmen;

# Connect to carmen
\c carmen
\i world.SQL
```
