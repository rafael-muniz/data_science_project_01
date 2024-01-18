# Data Science project 01

## Data Science project 01 - Applied Data Science Capstone

It is the Capstone project for the IBM Data Science Professional Certificate, using SpaceX's public data.
<br>

**<u>Files’ description:</u>**



* **Data Science Capstone - SpaceX - Rafael Muniz.pdf**: contains the final presentation of the project, with insights, explanations, code snippets, and graphs.
* **w1.1 - jupyter-labs-spacex-data-collection-api.ipynb**: in this notebook, data collection was performed making a get request to the SpaceX API. Also, some basic data wrangling and formatting was performed.  \
Libraries used: 
    * Pandas 
    * Numpy.
* **w1.2 - jupyter-labs-webscraping.ipynb**: this notebook performed the data collection through web scraping from Wikipedia of the SpaceX Falcon 9 launch records. Tasks performed: extraction Falcon 9 launch records from an HTML table from Wikipedia and then parse the table and convert it into a Pandas data frame. \
Libraries used:
    * Pandas
    * BeautifulSoup

* **w1.3 - labs-jupyter-spacex-Data wrangling.ipynb**: this notebook has the data wrangling process, meaning that some Exploratory Data Analysis (EDA) was performed to find some patterns in the data and determine what would be the label for training supervised models (Machine Learning models). \
Libraries used:
    * Pandas
    * Numpy 

* **w2.1 - jupyter-labs-eda-sql-coursera_sqllite.ipynb**: this notebook has the Exploratory Data Analysis (EDA) in SQL. It was used to understand the SpaceX Dataset, load the dataset into the corresponding table in the database, and execute SQL queries to answer insightful questions. \
Libraries used:
    * Sqlalchemy 

* **w2.2 - jupyter-labs-eda-dataviz.ipynb.jupyterlite.ipynb**: it has Exploratory Data Analysis (EDA) with Data Visualization (Scatter plot, bar chart, and line chart). \
Libraries used:
    * Pandas
    * Numpy
    * Matplotlib
    * Seaborn 

* **w3.1 - lab_jupyter_launch_site_location.jupyterlite.ipynb**: this notebook has site location analysis. In this lab the following tasks were performed: marked all launch sites on a map, marked successful/failed launches for each site on the map, and calculated the distances between a launch site to its proximities. \
Libraries used:
    * Pandas
    * Folium 

* **w3.2 - spacex_dash_app.py**: In this file, a Plotly Dash application was built for users to perform interactive visual analytics on SpaceX launch data in real-time. This dashboard application contains input components such as a dropdown list and a range slider to interact with a pie chart and a scatter point chart. \
Libraries used:
    * Pandas
    * Dash
    * Plotly 

* **w4.1 - SpaceX_Machine_Learning_Prediction_Part_5.jupyterlite.ipynb**: it was created a machine learning pipeline to predict if the first stage of the rocket would land successfully or not. The preparation tasks were: creating a column for the class, standardizing the data, and splitting into training data and test data. Later, when applying the machine learning models, the objectives were finding the best hyperparameters for them and find the model that performs the best using the test data. \
Machine Learning models used: Logistic Regression, Support Vector Machine, Decision Tree, and K Nearest Neighbors.
Libraries used:
   * Pandas
   * Numpy
   * Matplotlib
   * Seaborn
   * Scikit-learn
