# RecipeForReviews
An exploratory data project analyzing Montreal restaurant reviews to gain insights into ratings, sentiment, trends and more.

## Project Description
This project aims to leverage SQL and Python to analyze Yelp restaurant reviews from Montreal. The goal is to extract meaningful insights from restaurant reviews data with a focus on ratings, sentiments, trends, and other potentially interesting factors.

## Dataset
The data for this project is obtained from the Yelp Open Dataset. The dataset provides extensive data about various businesses and reviews, among which restaurant revies from Montreal have been extracted for analysis purposes in this project.

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
- Data Extraction - loaded and filtered the Yelp Open Dataset to obtain restaurant reviews from Montreal.
- Data Normalization - used pandas to normalize the data from the dataset, which included flattening the nested 'location' field

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

### Change in Project Scope (05-27-2023)
- Decided to change the project scope from originally analyzing Toronto restaurant reviews to Monreal due to the availability of a larger dataset.
- Downloaded the Yelp Open Dataset and decided to use this as the primary data source.

### Data Extraction from Yelp Open Dataset (05-27-2023)
- Loaded the Yelp Open Dataset which is in JSON format and filtered it for restaurant reviews from Montreal.
- Stred the filtered data in a pandas dataframe.

### Yelp Dataset Usage
This project utilizes the Yelp Open Dataset to collect and analyze Montreal restaurant reviews. By accessing and using the Yelp Dataset, I adhere to the terms and conditions outlined in the [Yelp Dataset Terms of Use](https://s3-media0.fl.yelpcdn.com/assets/srv0/engineering_pages/dc1cabe7cb95/assets/vendor/Dataset_User_Agreement.pdf).

Please note that my usage of the Yelp Dataset is subject to the restrictions and guidelines specified in the Terms of Use. I acknowledge Yelp as the provider of the data and services.
