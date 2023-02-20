# Simple-SparkSQL-ETL
Learning to use SparkSQL by building a simple ETL pipeline, the data was taken from

https://github.com/DataTalksClub/nyc-tlc-data/releases/download/fhv/fhv_tripdata_2019-01.csv.gz

Create a folder called data/\
Then place the .gz file inside the newly created data/ it should look like this
> data/fhv_tripdata_2019-01.csv.gz

Simply run simple_sparksql.ipynb in Jupyter Notebook\
Note: You need to have Apache Spark installed

# How it works
1. Extract: the script will read a gz file as a csv then convert it into dataframe
2. Transform: the data will be filtered as specified by the SQL statement
3. Load: save the data as a parquet and json file
