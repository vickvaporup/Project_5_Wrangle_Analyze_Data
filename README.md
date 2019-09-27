# Project_5_Wrangle_Analyze_Data
Data wrangling:  Assessing data Cleaning,  data Storing, analyzing, and visualizing  wrangled data Reporting

WeRateDogs Data Wrangling Project

Introduction

In this project the data will be gather from a variety of sources and in a variety of formats from Weratedogs (It is a Twitter account that rates people's dogs with a humorous comment about the dog) to assess its quality and tidines. Then data will be assessed and cleaned. Finally it will be acted through analaysis and visualization.

Gathering Data

It was obtained from three different resources: 

1.    twitter_archive_enhanced.csv  It was provided by Udacity. The file was downloaded manually from the link provided in the Udacity Project Details

2.    image_predictions.tsv file which was hosted in the Udacity Servers and was downloaded programmatically using the Request library via the link provided by Udacity.

3.    tweet_json.txt file. I could not set set up a twitter developer account due to my company’s proxy constraints. I followed the directions provided by Udacity to access the Twitter data without actually creating a Twitter account.

Assessing Data

The purpose of Assessing Data is to inspect data for two things Data Quality (content issues) and Lack of Tidiness (structural issues).

The data from the three different resources were saved in three different dataframes. tw_arc_df, image_predictions_df and tw_json_df. 

Programmatic assessment was run for the three dataframes. Some of the functions used were  .head, .info, .describe, .value counts .

Eight (8) quality issues and two (2) tidiness issues were identified and documented in the wrangle_act.ipynb

In regards to the quality issues, the criteria was : completeness, validity, accuracy, consistency.

In regards to the Tidiness issues, (e.g. each variable does not form a column, each observation does not form a row, each type of observational unit does not form a table) It was clear that there was an opportunity to combine the three dataframes into a single one. In order to achieve this, the column “id was” was renamed to “tweeted”.

Cleaning Data

This is where the quality and tidiness issues, which were identified in the Assess step, are remediated. The cleaning data was done using these three steps: Define, Code and Test. Programmatic cleaning was used for this stage via some functions like: rename, drop, merge, to_datetime, etc. For this project no manual cleaning was done.

Storing, Analyzing, and Visualizing Data for this Project



Finally, the resources used for this project were included at the footer of the file  wrangle_act.ipynb. The output of the wrangling process was stored in the twitter_archive_master.csv. 

The analyzed and visualized wrangled data  was included the wrangle_act.ipynb Jupyter Notebook. Three (3) insights and (3) visualization were produced.

 
Author

This project was completed by Victor Chicata.
