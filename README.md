This repository contains code for a movie recommendation system implemented in Jupyter Notebook.
The recommendation system uses the TMDB 5000 Movies dataset and utilizes natural language processing techniques to recommend movies based on similarity in their descriptions, genres, keywords, cast, and crew.

Files:
MovieRecommender.ipynb: Jupyter Notebook containing the code implementation.
tmdb_5000_movies.csv: Dataset containing movie details such as title, overview, genres, keywords, etc.
tmdb_5000_credits.csv: Dataset containing movie credits including cast and crew details.

Overview:
The Jupyter Notebook guides through the following steps:
Data loading and exploration.
Merging the two datasets.

Feature selection: Extracting relevant features like movie ID, title, overview, genres, keywords, cast, and crew.

Preprocessing text data: Cleaning and formatting text data for analysis.

Building the recommendation system: Using natural language processing techniques to calculate movie similarity and recommend movies.
Recommending movies based on user input.
Dependencies:
Python 3.x
numpy
pandas
matplotlib
seaborn
nltk
Usage:
Clone the repository.
Install the required dependencies using pip install -r requirements.txt.
Open and run the Jupyter Notebook MovieRecommender.ipynb to explore the code and run the recommendation system.




