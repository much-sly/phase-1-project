# MICROSOFT NEW MOVIE STUDIO.

## Name: Sylvia Muchiri.

## Introduction.
Movies are an interesting way to pass time and decompress from a long day of work. Microsoft is looking to make a new movie studio that produces the best selling genres that would be beneficial to them and also their fans. The only way possible is by analysing movie data collected from various sources in order to find the most popular movie genres and how they sell locally and all over the world. This analysis provides insights as to what genres are the most popular in order for the new movie studio to invest in for the best returns.


## Problem Statement.
Microsoft is interested in making a new movie studio but do not know where and how to invest in. This analysis aims at helping to make the right insights for the company to venture into for the best returns and promote the company's outlook for better returns by attracting more customers.

## Main Objective.
To come up with actionable insights that would be implemented by Microsoft to make a new movie studio.

## Specific objectives.
1. To find out which movie genre is the most popular.
2. To find out the returns of that genre both locally and worldwide.
3. To find out the production budget of that genre.

## Notebook Structure.
1. Data Collection
2. Read and check the data
3. Cleaning the data
4. Exploratory Data Analysis
5. Conclusions and Recommendations

## Data Understanding.
The data used is contained in a folder with zippedData that has movie datasets from:
.movie_basics
.movie_ratings
.bom.movie_gross.csv.gz
The data has varying rows and columns across all the datasets and only specific columns were used for the analysis and others which were not relevant for the analysis were dropped. The columns of the different dataframes were merged into other datafarmes that were used to make visualizations to help draw insights.However the data contains nan or missing values that had to be dealt with critically either by dropping or filling for easier merging.  

## Methodology.

### a) Data Wrangling.
This process involved finding missing values from the dataframes and filling them out or dropping them entirely if they were not relevant for the analysis. Also, formatting datatypes was at this point so that the datatypes would be consistent for easier plotting to avoid errors during creating the visuals. After cleaning up the data, the dataframes were joined in order to carry out analysis from the resulting dataframes.

### b) Exploratory Data Analysis.
. Univariate analysis was performed on the resulting dataframes after joining them to dispalay visuals to better understand the correlation and connection in the data or their relationships as well.
. From the analysis, musical and performing arts were the most popular in terms of returns locally.
. Also, musical and performing arts seemed to be the best performing genre worldwide.
. The production budget for Musical and performing arts was highest but only by a small margin from the other genres.
. There is no visible correlation between popularity and the returns the genres make.
. There is a positive correlation between domestic gross income and worldwide gross income across the genres.
. Despite Musical and performing arts being the best performing genre the average rating for darama was the highest.

## Conclusions.
. Musical and performing arts was the best performing genre both locally and internationally.
. The production budget for the genres vary but only by a small margin from each other.
. The Domestic and Foreign reurns have a positive correlation indicating that so long as a certain genre is popular at a time it will reap well both locally and internationally.

## Recommendations.
. Microsoft should consider exploring more data that shows if there is a relationship between seasons and genre popularity. This would help to know which genres to produce and in which season in time exactly.
. Microsoft should look to venture into Musical and Performing arts because it is the best selling genre and clearly the most popular.
. Microsoft should employ staff, that is directors and writers that are properly equipped with knowledge of movie genres and have better understanding of the market and what are the target groups and which of these are the greatest consumers.
. Microsoft should put up websites that would give customer feedback so that to satisfy the demands from the market and to be able to attract more customers.
. Check for performance of the genres at a time and take in for suggestions from customers in order to suit customer preferences to produce better movies with good quality.


