# Big-Data-Scaling-Youtube-Data-Analysis

 This project aims to help us gain insights on:
 1. What makes a video trending on Youtube.
 2. Can we predict the number of views on a video
 3. How does a region affect if a video would be trending or not? Do people in different regions want to watch different things ?

## Prerequisites

  Python was used to do visualization,modeling of the project

## Installation

  Pyspark, Pandas, Matplotlib, Seaborn are needed for Python. 

## Datasets and Feature Sources

  Data was collected from [Kaggle](https://www.kaggle.com/jyotmakadiya/top-trending-videos-youtube-2021). It contains variables like Video Title, Video description, Tags, Number   of Likes, Number of Dislikes, Number of comments etc. The data is available for many regions like India, USA, Germany, Japan, Russia etc. For our analysis we will be using   data from India, USA and Russia. The datatset contains 200 daily trending videos collected over few months.

  `US_data.csv` Youtube Videos Data for USA

  `IN_data.csv` Youtube Videos Data for India 

  `RU_data.csv` Youtube Videos Data for Russia 


## Pipeline

* Data processing and EDA
1. Run the file [EDA_Top_Trending_Videos.ipnyb]
2. The file uses libraries like seaborn, spark, numpy and pandas
3. Here we analyze the data as stand alone and also in terms of the business logic
4. In data preprocessing the dates formats were fixed, outliers were removeed and new columns created like time_diff
5. We also treated NA values by omitting them if necessary.
6. Analysis include the top trending channels per views
7. Content watched in different regions
8. Content produced in different region
9. Time taken for a video to trend from a the time it is being published.
10. Best time to upload the video based on region.
11. The comparison of view for top trending channels for different regions
12. Cosine Similarity as a test case but results cannot be used as reliable
13. Most common words in trending videos
14. Number of videos getting trending on a daily basis




* Modelling 

1. Run the data in the file [file_name_modelling.ipynb]
2. This file contains the code for modeling the data to predict the view count on youtube videos.
3. We use Gradient Boosted Regression and General Linear Regression model for this purpose.
4. In our final model we have used Word2Vec on the video title to add it to the feature vector and then used Gradient Bossted Tree Regression to predict the variable.
 

## Visualizations

Quick visualizations are scattered throughout the documents. We use barplots often just to see the results of the EDA which were usually counts.



