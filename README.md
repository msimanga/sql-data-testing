sql-data-testing
================

SQL scripts for testing ETL and data integrity.

## Background
A big chunk of data warehousing involves combining data from different databases. It is important that you continually test that your data between source and target systems is in sync. Changes in the source systems may not cause errors in your ETL process but have an effect on your data integrity. This is a series of scripts for different databases to create two tables and a stored procedure you can use to run regular tests on your data.
