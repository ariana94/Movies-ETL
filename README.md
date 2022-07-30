# Movies-ETL
In this project, we can view data pulled from Wikipedia (1990-2018) with information about movies, including budgets and box office returns, cast and crew, production and distribution, and so much more. I extracted the data from the sidebar into a JSON then loaded it into a Pandas dataframe. I also obtained a dataset on Kaggle with movie ratings from MovieLens with over 20 million ratings. Once all the data was cleaned and usable, I was able to tidy up each movie entry into a standard format. I was then able to merge the Kaggle and the Wiki data using the IMDb ID column. I then did some further cleaning where the two sets of data overlapped with redundant data. Once everything was sorted and filtered, I moved the Pandas data frames over to an SQL database called movie-data. Doing this allows us to run more specific queries across all the information we have collected. Now we have created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.
# Final queries
movies query for row count
![movies_query](https://user-images.githubusercontent.com/19378130/179380395-653be2d7-ca57-4f12-b81d-865b8ad96a20.png)

rating query for row count
![ratings_query](https://user-images.githubusercontent.com/19378130/179380429-3c541210-fb68-4baa-8190-0811c552a1ac.png)
