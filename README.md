# DataCleaning
The cleaning of IRI Data Set as part of DSE220 final project\s\s

# Connecting PG to Ipython:
- install ipython-sql module(https://pypi.python.org/pypi/ipython-sql) and use the following commands to connect to your PG server: \s\s
- pip install ipython-sql\s\s
- brew install postgresql\s\s
- pip install pgsycopg2\s\s
- brew install --upgrade openssl\s\s
- brew unlink openssl && brew link openssl --force\s\s
- %load_ext sql\s\s
- %%sql postgresql:http://sharknado-dse.ceg3hdkdq8l0.us-east-1.rds.amazonaws.com/\s\s
- select * from character\s\s
- where abbrev = 'ALICE'\s\s