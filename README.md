# World Happiness Weighted Factors
Week 4 Tableau Project

[Please find the Tableau Workbook here](https://public.tableau.com/profile/shelley.obery7247#!/vizhome/World_happinessData/CalculatingHappiness)

*Shelley Obery*

*Data Analytics, Berlin, 28-06-2020*

## Content
- [Project Description](#project-description)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The World Happiness Weighted Factors Project looks at how the factors used to calculate the Happiness Report are actually weighted differently for every country. Outlining these differences could offer insights into the situations and perceptions of countries and open up questions as to why different aspects hold more or less importance.
              
## Workflow
- I first searched Kaggle for useable data, before deciding on a topic. I came across this data-set (see link below) and thought it was an interesting insight into the calculation for the happiness ranking. At first I thought it was biased, but no single number can explain a country's happiness (i.e. a high GDP does not exactly equal more happiness).
- Fortunately, the data was quite clean, unfortunately it was separated in different files by year and author(s) had used different column names. After a quick cleanup, adding a year column and a few appends, the data was ready for export. I was not able to figure out how to join the data-sets in Tableau, hence the appending of dataframes in pandas.
- I then sketched out a few rough drafts to plan out what my visualisations would look like. Then did everything completely differently once I had the data in Tableau, because I was not yet very familiar with what was possible.
- First came the worksheets, starting with a general outline and then illustrating the difference of weighting.
- I found the story to be the most tricky as the sizes of the dashboards I created did not correspond with the story size.
- I created the repo, pushed my changes and saved my Tableau file to Tableau Public.

## Organization
The repo contains a jupyter notebook for data cleaning, the original csv files in "world_happiness_data" and the clean combined csv in "data".

## Links

- [Repository](https://github.com/soberi/world_happiness)
- [Link to Kaggle data](https://www.kaggle.com/unsdsn/world-happiness)
- [More info on the Happiness Report](https://www.trackinghappiness.com/happiness-index-2018/)
