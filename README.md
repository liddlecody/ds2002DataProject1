# ds2002DataProject1
## ETL Pipeline Description
#### This pipeline for pulling NBA Player Statistics pulls from the BalldontlieAPI and the Kaggle NBA Stats dataset. Download 
the nba_stats_kaggle.csv file from the repository then upload it into your environment. My key for Balldontlie is included but feel free to replace it with
your own.
#### The first six cells complete all essential imports as well as definitions for helper functions in the main ETL script.
#### Running the main ETL script loads the data from both sources and provides descriptions of both. Then it completes all necessary transformations and cleaning, then merges 
them into one common dataset. Then some analysis is done providing insight into various metrics related to the player statistics. The data is also saved into JSON and a CSV. 
#### The convert_format() function can be used to change between JSON and CSV, and the load_to_sqlite() function can be used to change to a SQL database. All types can be reached from one another 
using pandas data frame as an intermediary format.
#### Lastly, the data frame is loaded into an SQLite database where it can be queried, modified, etc.
