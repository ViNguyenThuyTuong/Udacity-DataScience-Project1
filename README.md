# Udacity-DataScience-Project1
Udacity DataScience Nanodegree Project 1 - Stack Overflow Data Exploration & Analysis

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Data Descriptions](#data)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code was developed and tested using Python 3.6.5, pandas version 0.25.0, seaborn version 0.8.1, matplotlib version 2.2.2, and squarify version 0.4.3.    

## Project Motivation<a name="motivation"></a>

For this project, I'd like to use Stack Overflow 2021 data to better understand:

    1) Which countries have the highest percentage of people using Stack Overflow?
    2) What demographic are most of our Stack Overflow users in?
    3) Which programming languages are most used in 2021 and which ones would become a trend in 2022?
	4) Which databases are most used in 2021 and which ones would become a trend in 2022?

## Data Descriptions <a name="data"></a>

The full set of files related to this course are stored on insights.stackoverflow website, refer following link: https://insights.stackoverflow.com/survey 2021 part.

The following Airbnb activity is included in this Seattle dataset:

  1. `README_2021.txt`: a text file with descriptions about the data
  2. `survey_results_public.csv`: CSV file with main survey results, one respondent per row and one column per answer
  3. `survey_results_schema.csv`: CSV file with survey schema, i.e., the questions that correspond to each column name
  4. `so_survey_2021.pdf`: PDF file of the survey instrument
  
  For this analysis, I only used the `survey_results_public.csv` file.

## File Descriptions <a name="files"></a>

There is a Jupyter notebook in this repository to showcase work related to the above questions.  Each of the notebooks is exploratory in nature, and include markdown cells to explain and describe the visualization and exploration process.  

The notebooks that are related to the analysis presented in the medium blog (see below) are located here:

    1) airbnb/ipynb/seattle_airbnb_neighborhood_exploration.ipynb

The other notebooks in the scratch_ipynb folder include additional related exploratory analaysis that preceded the two notebooks listed, and include some potentially useful information, but are outside the scope of this project.

## Results<a name="results"></a>

The main findings of the code can be found at the post available here: [whered-the-hippies-go](https://medium.com/@bridgethass/whered-the-hippies-go-aee4b0876dc7).

## Licensing, Authors, Acknowledgments <a name="licensing"></a>

Data is provided by [insideairbnb](http://insideairbnb.com/get-the-data.html) and hosted on [kaggle](https://www.kaggle.com/airbnb/seattle/data), which also includes the licensing information. The code here is licensed under open source GNU General Public License v3.0, and is free to use as you wish, with no guarantees :)
