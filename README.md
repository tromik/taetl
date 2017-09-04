# taetl
ETL Client Using Python 3

## courier
A courier is a dataflow task that can be comprised of a source(s), a target(s),
a write method (insert, update, upsert, delete), field-level mappings,
and pre and post tasks.

## source
A source is comprised of a source type (e.g. Postgres database, csv), a query,
and credentials.

## target
A target is comprised of a target type (e.g. Postgres database, csv) and
a delivery method (raw SQL, adapter, ORM, etc.).

## concepts
- Easy to use configuration file to identify sources and targets and environments
- Pipeline of chained couriers to create dependent and independent couriers

## libraries
- pyscogp2 - Postgres native (http://initd.org/psycopg/)
- pymssql - MS SQL Server native (http://pymssql.org/en/stable/)
- pyodbc - ODBC for multiple databases (http://mkleehammer.github.io/pyodbc/)
- SQL Alchemy - Postgres and MySQL ORM (https://www.sqlalchemy.org/)
- petl - General purpose ETL (https://petl.readthedocs.io/en/latest/#)
- odo - Data migration between various systems (http://odo.pydata.org/en/latest/index.html)
- pandas - Data structure and analysis (http://pandas.pydata.org/)
- bubbles - Data processing framework (http://bubbles.databrewery.org/)
