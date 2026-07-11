# r_dbi_project
Hi! This project focuses on connecting to a database and running 
SQL queries in R using the DBI and RSQLite packages. We connect 
to an in-memory SQLite database, write three car datasets as tables, 
and query them using SQL commands — hope you enjoy and leave some feedback!

## What This Project Covers
- DBI — dbConnect, dbWriteTable, dbListTables, dbSendQuery, 
  dbFetch, dbClearResult, dbGetQuery, dbDisconnect
- RSQLite — SQLite in-memory database connection
- SQL — SELECT, WHERE, GROUP BY, ORDER BY DESC, LEFT JOIN, LIMIT
- dplyr — tibble construction for dataset creation
- librarian — shelf() for package management

## Key Concepts Demonstrated
- dbSendQuery vs dbGetQuery — manual vs automatic result handling
- dbClearResult — freeing memory after each query for performance
- SQL LEFT JOIN vs R left_join() — explicit SELECT controls output in SQL
  unlike R which handles duplicate columns automatically
- DBI is interchangeable across database systems — swap RSQLite 
  for RPostgres, RMySQL etc with the same syntax

## Dataset
Three self-made car datasets — car_brands, car_companies, 
and car_parts — originally built for the R Joins Project

## Notes
README written with AI assistance. All R code written organically.