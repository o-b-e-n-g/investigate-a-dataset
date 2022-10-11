# Investigate A Dataset
 
Python Project Investigating a Dataset


## Dataset

This data set contains information about over 10,000 movies collected from The Movie Database (TMDb) over a period of years from 1960 to 2015. The data set contains information about movies in tables such as the title, casts and director and it also contains information about the perfomance of movies in tables such as budget, revenue and popularity.


## Aim of Investigation

We will seek to answer questions mainly related to the profitability of the moves. Three questions we would look to answer from this data set are:

Which years do movies have the most profits?
What is the relationship between the profit of movies and the following:
     a. The Budgets
     b. The Popularity
What are the most profitable genres?

## Summary and Conclusion

This analysis was performed on a data set containing information about over 10,000 movies collected from The Movie Database (TMDb) over a period of years from 1960 to 2015. The data set contains information about movies in tables such as the title, casts and director and it also contains information about the perfomance of movies in tables such as budget, revenue and popularity.

As part of the data wrangling process, certain issues were idientified certain issues which were resolved in the data cleaning process. These issues included:

1. Dropping duplicated rows
2. Dropping movies with no budgets or revenues
3. Dropping irrelevant columns

From our analysis of the dataset, we observed the following:

The year 2015, the most current year as the most profitable year. However, movies/the movie industry had gradually grown more profitable with every new year. cross the top 10 profitable years, there were only dips in profitability from 2009 to 2010 and 2011 to 2012.
Budgets and Profits and Popularity and Profits are both moderately correlated. However, there is a stronger relationship between profits and popularity than between profits and budgets.
Over the span of 55 years, adventure movies made the most profits, followed by action and comedy.


## Summary and Conclusion

The following are sources used for research during this project: 

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.nlargest.html

https://www.geeksforgeeks.org/python-seaborn-regplot-method/#:~:text=regplot()%20%3A,for%20estimating%20the%20regression%20model.

https://seaborn.pydata.org/generated/seaborn.regplot.html

https://www.geeksforgeeks.org/python-pandas-dataframe-corr/#:~:text=corr()%20is%20used%20to,the%20dataframe%20it%20is%20ignored.

https://stackoverflow.com/questions/42579908/use-corr-to-get-the-correlation-between-two-columns

https://stackoverflow.com/questions/45487145/pandas-correlation-between-list-of-columns-x-whole-dataframe

https://stackoverflow.com/questions/12680754/split-explode-pandas-dataframe-string-entry-to-separate-rows

https://stackoverflow.com/questions/72470124/columns-must-have-matching-element-counts-pandas

https://stackoverflow.com/questions/69534014/how-to-fix-columns-not-having-matching-element-counts-when-using-explode-in-pyth
