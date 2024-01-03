# Project Instructions

Find the number of unique companies and their total carbon footprint PCF for each industry group, filtering for the most recent year in the database. The query should return three columns: `industry_group`, `num_companies`, and `total_industry_footprint`, with the last column being rounded to one decimal place. The results should be sorted by `total_industry_footprint` from highest to lowest values.

<br>

## RESOURCES

##### Check resources that can help you solve the problem.

### SLIDES
#### [COUNT() with DISTINCT](https://campus.datacamp.com/pdf/web/viewer.html?file=https://projector-video-pdf-converter.datacamp.com/29303/chapter1.pdf#page=8)
#### [GROUP BY with ORDER BY](https://campus.datacamp.com/pdf/web/viewer.html?file=https://projector-video-pdf-converter.datacamp.com/29303/chapter4.pdf#page=16)

### LESSONS
#### [Summarizing subsets](https://campus.datacamp.com/courses/intermediate-sql/aggregate-functions-3?ex=4)
#### [Subqueries inside WHERE and SELECT](https://campus.datacamp.com/courses/joining-data-in-sql/subqueries-4?ex=5)

<br>

## GUIDES

### How to approach the project
1. Executing the query

### 1Executing the query
Write your query, which will produce an output saved as a pandas DataFrame called `carbon_emissions_by_industry`. Select the columns of interest and `GROUP BY` industry.