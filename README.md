# Project Name: TMDb_Movies_data_analysis

----
# Introduction

This is an analysis done on TMDb movies dataset of 1960 to 2015

The dataset contains information about 10,000 movies collected from TMDb Database including user ratings, budget for each movie and revenue.

Below is the list of columns names in our dataset and their significance

`id` - This is a unique identifier for each movie

`popularity` - A numeric quantity specifying the movie popularity

`budget` - The cost in which the movie was made

`revenue` - The worldwide revenue generated from the movie

`original_title` - The title of the movie before translation or adaptaion

`cast` - The name of lead and supporting actors

`homepage` - A link to the homepage of the movie

`director` - The directors of each movie

`tagline` - The movie's tagline

`overview` - A brief description of the movie

`runtime` - The running time of the movie in minutes

`genres` - The genre of the movies; Action, Drama,Adventure etc..

`Production_companies` - The production house of the movie

`release_date` - The date the movie was released

`vote_count` - The count of votes the movie received

`vote_average` - Average rating the movie received

`release_year` - The year the movie was released

----
# Research Question(s) for Analysis
This dataset will be analysed to answer the foll0ing the following questions;

 1. What year did TMDb Movies made the highest profit?
 2. Which TMDb movie has the highest profit expressed as a percentage of its budget?
 3. What is the correlation between the attributes of our TMDb movies dataset?
 
----
# Objective of Analysis
The objective of our analysis are;

1. To identify the year TMDb movies made the highest profit
2. To determine the movie that has the highest percentage, when profit is expressed as a percentage of its budget.
3. To ascertain the correlation between different attributes of TMDb dataset.


----
# Exploratory Analysis

![The Top Five Years With the Highest Profit](https://user-images.githubusercontent.com/74934727/181943705-95bcd2ba-9907-49c1-8cff-9be4aa8fa353.png)


![The First Five Movies with the Highest Profit relative to the budget](https://user-images.githubusercontent.com/74934727/181943830-c21e1978-8880-4332-a0d9-9b4461623867.png)


![Correlation of TMDb Movies dataset attributes](https://user-images.githubusercontent.com/74934727/181943846-6c1c8315-5c2d-40fb-b43b-c04d2df7326e.png)



----
# Conclusion and Findings
1. From our analysis we were able to ascertain that TMDb movies generated the highest profit in 2015.
2. Also, we discovered that From Prada to Nada movie has the highest profit in relative to budget.
3. We found that;
   `revenue` and `popularity` is highly correlated with `vote_counts`.
   `revenue` is highly correlated with `budget`.
   `vote_counts` is highly correlated with `profit`.

----
# Limitations
The filtered dataset contained vast number of Null values of which certain revenue values where dropped when budget is zero and budget when revenue is zero as well. Also, I dropped many columns from the dataset which where not needed for my analysis.

