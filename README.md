# DataCleaning
The cleaning of IRI Data Set as part of DSE220 final project

# Connecting PG to Ipython:
- install ipython-sql module(https://pypi.python.org/pypi/ipython-sql) and use the following commands to connect to your PG server: 
-- pip install ipython-sql
-- brew install postgresql
-- pip install pgsycopg2
-- brew install --upgrade openssl
-- brew unlink openssl && brew link openssl --force
-- %load_ext sql
-- %%sql postgresql:http://sharknado-dse.ceg3hdkdq8l0.us-east-1.rds.amazonaws.com/
-- select * from character
-- where abbrev = 'ALICE'