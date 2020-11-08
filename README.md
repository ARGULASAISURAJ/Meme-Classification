# Meme-Classification
This study aims to detect sarcasm/hateful memes by using text and image features in unimodal(using only text) and multimodal(using text and image data) fashion to see the performance of the classifier in detecting sarcasm/hate.

Link to download Raw memes data-

https://drivendata-competition-fb-hateful-memes-data.s3.amazonaws.com/XjiOc5ycDBRRNwbhRlgH.zip?AWSAccessKeyId=AKIARVBOBDCY4MWEDJKS&Signature=18jU0Xxm%2FBfvPASl32CcUuTXVEo%3D&Expires=1604709308

Files- Format:-

1. **Text-mining-Data-preparation-Final.ipynb**
--> The first section code is about extracting text, Objects and Labels from Google API using Google API Secured key. Merging the labelled data from annotators and raw prepared data. 
    Twitter memes extraction program is in Another file with name- **twitter_memes_extraction.ipynb**

The output labels are in the CSV file ->Full_data.csv
Labeled memes taken into model consideration-> Final_df.csv

2. **Text_Analytics_Project_PreProcessing-Final.ipynb**
--> This is the file where we did text cleaning process from the Final_df.csv - the cleaned text output is in final_dataframe.csv, on which we performed Exploratory Data Analysis and Modelling

3. **Text-mining-Data-Exploratory-Data-Analysis-Final.ipynb**
--> This is the file in which we did our exploratory analysis on the cleaned text output file.

4. **Text-mining-Data-Modelling-Final.ipynb**
--> File in which we did modelling on only text and built Multimodals on Text as well as Images.

5. ** **
-->This file can be run on GPU in Google collab. This is facebook community pytorch implementation of prodcution ready code for Facebook AI research project. we made minor changes to this code, so that we can compare the performaceof our model with theirs.
