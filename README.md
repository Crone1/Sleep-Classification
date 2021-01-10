# Project Explanation
The project was done by myself and GitHub user *'fitzpai3'* as part of the module *'Advanced Machine Learning'*. The purpose of this project was to classify a subjects sleep stage at any given point in time based on their Apple Watch data. The data recorded by this Apple Watch was the subjects heart rate, their step count and their acceleration in all directions.

Our job was to model the data for all the subjects based on a manually assigned sleep label and then to be able to classify new data and assign a sleep label to this.
These sleep labels ranged from sleep 0-5 with 0 being awake and 5 being REM sleep.

The code for completing this task was done using google collab for collaboration purposes and to get experiance using this platform. I then coppied the developed code into this GitHub repository.

# Notebook Details
This code consists of three notebooks with each notebook being numbered by the order it should be run in:

1. Introduction and Data Preperation (1-intro-and-data-preperation.ipynb)
   - The data was not in the nicest of formats so this involved a lot of code to format it properly
2. Feature Extraction (2-feature-extraction.ipynb)
   - We used the tsfresh library for this,  in particular, its extract_features and select_features functions
3. Classification and Results (3-classification-and-results.ipynb)
   - Here we used a number of models in the Scikit-learn package and also carried out several experiments
