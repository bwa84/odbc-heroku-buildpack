# Heroku buildpack: ODBC Driver 18 for SQL Server

This repository is based on https://github.com/matt-bertoncello/python-pyodbc-buildpack which is for driver 17.5.

The Labour auth-service requires the ODBC Driver and Heroku requires openssl v3+, whereas the driver 17.5 requires openssl 1.0 or 1.1.

This repository provides ODBC Driver 18 to resolve that issue.

