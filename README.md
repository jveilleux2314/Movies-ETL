# Movies-ETL

I helped Britta pull movie data from Wikipedia and Kaggle for the Hackathon and instead of giving all the ratings from her employer we pulled over 20 million ratings from MovieLens which is run by a research team called GroupLens. 

With this data we had to extract it from the csv files and json files and since the data was raw and not at all workable - we had to transform it into clean data with no duplicates, no missing data, filter out unnecessary data such as TV shows (when our concentration is movies) , and fix the column names so that I would be able to accurately merge the data sets. 

# Process

I used multiple processes to acheive this clean dataset, multiple of which I have learned from previous projects but I was able to integrate new skills such as using lambda functions, def fuctions, and regex. 

- [x] Python
- [x] SQL
- [x] Jupyter Notebooks
- [x] PG Admin
- [x] Pandas
- [x] json files
- [x] csv files
- [x] numpy
- [x] def functions
- [x] lambda functions
- [x] regular expressions (Regex)

  * import functions
  * define functions
  * Correct column names
  * filter out TV shows and unnecessary data
  * drop duplicate data
  * merge dataframes
  * export to Pg Admin- millions of data rows

<img width="858" alt="ratings_query" src="https://user-images.githubusercontent.com/78769464/116787514-1aee1d00-aa6a-11eb-8eae-eb6625eee760.png">

<img width="330" alt="movies_query" src="https://user-images.githubusercontent.com/78769464/116787515-1de90d80-aa6a-11eb-816c-fb75f80ecff4.png">




