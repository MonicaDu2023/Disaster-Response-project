# Disaster-Response-project
The project is to build a Natural Language Processing (NLP) model and show result in a web app. This project is divided in the following key sections:
* Data Processing: ETL Pipeline to extract data from source, clean data and save them in a database
* Machine Learning Pipeline to train a model able to classify text message in categories
* Web App to show model results in real time.
# Installation
* Python 3.5+ (I used Python 3.7)
* Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn
* Natural Language Process Libraries: NLTK
* SQLlite Database Libraqries: SQLalchemy
* Web App and Data Visualization: Flask, Plotly
# File Descriptions
* App folder including the templates folder and "run.py" for the web application
* Data folder containing "DisasterResponse.db", "disaster_categories.csv", "disaster_messages.csv" and "process_data.py" for data cleaning and transfering and ETL Preparation Notebook prsent data processing step by step
* Models folder including "classifier.pkl" and "train_classifier.py" for the Machine Learning model and ML Pipeline Preparation Notebook present Machine Learning Model step by step
* screenshot folder contains images show project result
# Executing Program
* Run the following commands in the project's root directory to set up your database and model:
1. To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
2. To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl
* Run the following command in the app's directory to run your web app. python run.py
* Go to http://0.0.0.0:3001/
# Licensing, Authors, Acknowledgements
[Figure Eight](https://appen.com/) for providing the relevant dataset to train the model
