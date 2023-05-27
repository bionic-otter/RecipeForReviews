# RecipeForReviews
An exploratory data project analyzing restaurant reviews to gain insights into ratings, sentiment, trends and more.

## Project Description
This project aims to leverage SQL and Python to analyze Yelp restaurant reviews. The goal is to extract meaningful insights from restaurant reviews data with a focus on ratings, sentiments, trends, and other potentially interesting factors.

## Dataset
The data for this project is obtains from the Yelp Fusion API. The API provides access to various Yelp businessess and reviews data.

## Tools & Libraries
- Python
- SQL
- Jupyter Notebook
- Git & Github

## Setup & Installation
- Installed Anaconda distribution which includes Python and Jupyter Notebook.
- Created a GitHub repository to manage and track versions of the project.

## Methods Used
- Run Jupyter Notebook server using Anaconda Prompt and navigate to the project folder.
- Data Extraction - used the Yelp Fusion API to obtain data about restaurants in Toronto
- Data Normalization - used pandas to normalize the data from the API, which included flattening the nested 'location' field

## Project Steps
### Project Conceptualization (05-25-2023)
- Identified the objective of the project - analyzing restaurant reviews to gain insights into various aspects of the reviews such as restaurant ratings, sentiment of revies, trends over time, etc.
- Selected Yelp Fusion API as the data source for the project

### GitHub Repo Creation (05-25-2023)
- Created a new GitHub repo named "RecipeForReviews"
- Initialized the repo with a README file for documenting the project steps and methodologies.

### Jupyter Notebook Setup (05-25-2023)
- Installed and setup Anaconda and Jupyter Notebook on local machine
- Created a new Jupyter notebook titled "Data_Extraction_Preprocessing.ipynb" in the project directory

### Data extraction using the Yelp Fusion API (05-27-2023)
- Created a Python code block to fetch data using the Yelp Fusion API related to restaurants in Toronto.
- Stored the fetched data in a pandas dataframe.

### Data Normalization (05-27-2023)
- Tried to flatten the nested 'location' field in the data using 'pd.json_normalize()', but encountered a TypeError.
- Resolved the error by accessing the 'location' field directly instead of trying to flatten it.
- Merged the original dataframe and the location details into a new dataframe.


### Yelp API Usage
This project utilizes the Yelp Fusion API to collect and analyze restaurant reviews. By accessing and using the yelp API, I adhere to the terms and conditions outlined in the [Yelp API Terms of Use](https://www.yelp.com/developers/api_terms). 

Please note that my usage of the Yelp API is subject to the restrictions and guidelines specified in the API Terms of Use. I acknowledge Yelp as the provider of the data and services used in this project.
