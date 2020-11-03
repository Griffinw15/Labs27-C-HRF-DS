# Labs 27C Notebooks

This directory contains all notebooks used by Labs 27C, this includes reworked(inherited) notebooks and any additional.

## Contents

• JSON (folder)

  -- Data_Final_Jsonified.ipynb -> Reads in JSON from 2020PB for a dataframe, 846 API is used to grab additional source links. Latitude and Longitude are then created from geocoding, 'latest_incidents.csv' is created from the dataframe, finally it is JSONified.
  
  -- Send_Data_JSON_for_Testing.ipynb -> Contains function 'run_update' which updates the backlog database with reddit data (a feature created by labs25). Geolocation is generated from city/state. 
  

• data exploration (folder)

  -- Data_Exploration_846_and_2020OB.ipynb -> EDA of data from 846 as well as 2020PB
  
  -- Data_Exploration_PRAW.ipynb -> EDA of reddit API including creation of keyword tags list and looking to improve spaCy NLP.
  
  -- Data_Exploration_PRAW_2.ipynb -> EDA of labs25 .env usage with PRAW
  
  -- Data_Exploration_with_newspaper3k.ipynb -> EDA of newspaper3k and binary classification of police brutality instances
  

• modeling (folder)

  -- Model_RF_V1.ipynb -> A random forest classification model 
  
  -- Reddit_NLP_Classification.ipynb -> Methodology around NLP tags and lemmas from reddit API news titles
  

• Labs 27C Data Custody Diagram (.png)
