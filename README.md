# CMSC320-Final

To view our project navigate [here](https://jasminepparekh.github.io/CMSC320-Final/):

Data Kaggle Link: 
https://www.kaggle.com/PromptCloudHQ/imdb-data

CSV used:
IMDB-Movie-Data.csv

## Steps:
- Clean Up Data
  - Done:
    - Made 'Rank', 'Year', 'Runtime (Minutes)', 'Rating', 'Votes', 'Revenue (Millions)', 'Metascore' all into numeric types
    - Made 'Genre' and 'Actors' into lists of strings
    - Rest of datatypes should be strings
- Analysis:
  - Analyze Revenue vs Genre
  - Analyze Revenue vs Director
  - Analyze Revenue vs Actors
    - Actors are points based on ranking
    - Sum up the actor's points who are on the ranking list and avergae by number of actors who are also in the ranking list
