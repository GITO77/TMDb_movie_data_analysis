#  TMDb movie data analysis
## by Greatness Okeremeta


## Dataset

> This data set contains information about 10,000 movies collected from The Movie Database (TMDb) from 1960 to 2015.


## Summary of Findings
>The aim of this project was to answer 2 questions: the most popular genres from year to year and the properties associated with movies that had high revenues. In 1960, 2 movie genres (Horror & Thriller) were equally the most popular genres for the year; every other year under review, had only one top genre. The Animation and Fantasy genres topped most years under review (15 and 10 years respectively) as the most popular genres. Although Drama was the most popular genre in 1966, it had the lowest popularity rating (~0.49) of all the years reviewed while Science Fiction in 2015 had the highest popularity rating (~7.6) of all the years reviewed. Movies with higher revenues, tend to have higher popularity ratings, budgets and profits than those with lesser revenues. There was no correlation between revenue and movie runtime.


## Key Insights
> The project uses NumPy arrays and Pandas Series and DataFrames. I started off by wrangling the dataset to ensure that it was suitable for analysis. Guided by the research questions,I engaged in Exploratory Data Analysis to produce suitable and relevant insights, I also included user-defined functions to avoid repetitive code. I investigated the stated questions from multiple angles, exploring the following variables in relation to the primary questions - release_year, popularity, genres, profit_adj, revenue_adj, budget_adj and runtime. Single-variable (1d) and multiple-variable (2d) explorations were carried out on these variables. Relevant statistics was computed throughout the analysis when an inference was made about the data. The project's visualizations were varied and showed multiple comparisons and trends.


## Limitations
> There were multiple rows with null values in the genres, budget and revenue columns.These null values had to be removed so as not to affect the final results. A significant number of the movies had multiple genres assigned to them. I had insufficient insight into the computation of the values in the vote_count and vote_average columns. If more insight is provided, these columns can be used for further investigation.
