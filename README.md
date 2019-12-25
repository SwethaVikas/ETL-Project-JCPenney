# ETL-Project-JCPenney

Extraction
We scraped Data from JCP website for data on booties, and get the price for using multipler pages. The idea is to get the range of price for booties for one website and apply to others. Build a dataframe from multiple websites and compare the prices from various sources

Transformation

Our first steps in cleaning up the datasets involved figuring out which variables were not relevant.Some of the data showed higher prices for non relevant items that was suggested. 

Load

The last step was to transfer our final output into a Database. We created a database and respective tables to match the columns from the final Panda’s Data Frame using Postgre and then connected to the database using SQLAlchemy and loaded the result.
