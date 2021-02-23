# Movies-ETL
Project to create a pipeline to extract, transform and load movie data. Data is sourced from raw JSON and CSV data from Kaggle and Wikipedia. Jupyter notebooks, Python and Pandas used to extract and transform the data. The resulting DataFrame is loaded into PostgreSQL using SQAlchemy. 
Data was cleaned for alternate titles, duplicates due to alternate languages, and budgets and runtime errors due to alternate formatting.
It was assumed that the Kaggle data was more complete for Title, Release Date, Language and Production Company and duplicate columns from Wikipedia were dropped. It was also assumed that Kaggle data was more complete for Runtime, Budget and Revenue so Wikipedia data was used where there was no Kaggle data and Wikipedia data was dropped if there was a duplicate. 
This project was part of the UC Berkeley Data Analytics Boot Camp.


### Tech Used
- Jupyter Notebooks
- Python 3
- JSON
- Pandas
- NumPy
- SQLAlchemy
- Lambda

#### Code Sample
![Code Sample](/image/code.png)