# WeatherForecaster
Data Science Capstone 2 (Springboard)

A comprehensive analysis on a weather dataset for Mainland Europe across 18 separate locations between the years 2000-2010. Project includes:
- Jupyter Notebooks that include the python code
- Data folders containing the datasets used throughout the analysis
- Library folder that holds some helper functions
- Models folder that contains the models created from the analysis
- Model Metrics file that contains details for each model
- Model Report that discusses the entire process of the analysis
- A Powerpoint presentation that compiles all the information of the analysis into a real life scenario where the analysis is put to good use

Below each section listed above is described in further detail.

[Link to Original dataset](https://www.kaggle.com/datasets/thedevastator/weather-prediction/data)

## Jupyter Notebooks
There are 5 separate notebooks each containing code performing a different step in the data science method. Beginning from data wrangling all the way up to documentation, this is where the core of the project is. Python packages and datasets are imported into each notebook, analyzed and then modified, new datasets are then stored in separate folders. Code creating models fitted to modified datasets can also be found in the respective notebooks.

1. **01_problem_statement (Not a Jupyter Notebook)** - details the problem and sets up the context for the analysis
2. `02_data_wrangling` - cleans the weather data 
3. `03_exploratory_data_analysis` - analyzes the data to detect trends and correlations to find potential predictor features for the mean temperature
4. `04_preprocessing_and_training` - proprocesses the data so that it is ready to be trained and testing multiple models to find good candidates for further tuning
5. `05_modeling` - from previous notebook, takes the best models and conducts hyperparameter tuning to optimize the best models, saves the models to the `models` folder
6. `06_documentation` - graphs out multiple performance metrics between all the models of interest during the analysis

## Folders
- ### raw_data
    Folder that holds the raw weather dataset from Kaggle, can also be found by visiting the above link.
- ### modified_data
    Folder contain modified versions of the raw dataset better suited for exploratory data analysis and modeling.
- ### library
    Folder containing helper functions, mainly to help with writting to files. Created by Springboard.
- ### models
    Folder holding all of the models that were created to predict the mean temperature of tomorrow. There are 2 subfolders within each holding 18 separate models, each specialized to a specific location.

## Other Files
- ### Model Metrics
    A text file detailing basic details such as parameters, hyperparameters, and scoring metrics for each of the models. A total of 36 models are listed and used.

- ### Final Report
    A word document detailing each step throughout the analysis, beginning with the problem statement and ending with a conclusion as well as notes for potential further analyses that can be done.

- ### Weather Forecaster Presentation
    The final presentation summarizing the entire analysis process suitable to both a technical and non-technical audience.