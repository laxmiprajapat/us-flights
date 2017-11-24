# us-flights
Analysis of US domestic flights data to extract insights in relation to flight delays. 

Author: Laxmi Prajapat
Last updated: 23/11/17

Raw data files required:
- data-flights_large.csv/data-flights_medium.csv (not on github)
- data-weather.csv (not on github)
- states.csv
- us census bureau regions and divisions.csv
- airport-codes.csv
- airlines.csv
- airline-id.csv
- airline_ratings_subset.csv
- ATL-weather-2008.csv
- passenger_volumes.csv

Tools used:
- Jupyter Notebook (Python 2.7)
- Tableau

Python libraries used:
- pandas (0.18.0)
- numpy (1.11.1)
- re (2.2.1)
- sklearn (0.17.1)
- nltk (3.2.1)
- textblob (0.13.1)

Jupyter notebook files:
- us-flights-analysis.ipynb (for all data preprocessing/NLP/weather data extraction)

Tableau files:
- tableau-code.txt (snippets of Tableau logic)
- initial-exploration.twb
- us-flights-dashboard.twb (uses an older data-flights-draft_2.csv file)

Output files:
- data-flights-final.csv (not on github)
- monthly-ratings-final.csv
- month-ratings-my.csv
- wordcloud_input.csv
- weather-data-daily-final.csv (not on github)
