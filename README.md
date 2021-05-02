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




* Modelling 

1. Run the data in the file [file_name_modelling.ipynb]
2. This file contains the code for modeling the data to predict the view count on youtube videos.
3. We use Gradient Boosted Regression and General Linear Regression model for this purpose.
4. In our final model we have used Word2Vec on the video title to add it to the feature vector and then used Gradient Bossted Tree Regression to predict the variable.
 

## Visualizations

Quick visualizations are scattered throughout the documents. We use barplots often just to see the results of the EDA which were usually counts.



