# Meme-Classification- Text-Analytics

![meme](https://github.com/ARGULASAISURAJ/Meme-Classification/blob/main/meme.jpg)

This study aims to detect sarcasm/hateful memes by using text and image features in unimodal(using only text) and multimodal(using text and image data) fashion to see the performance of the classifier in detecting sarcasm/hate.

## Table of Contents:

1. [Data preparation](#Data-preparation)
2. [Pre-processing](#Pre-processing)
3. [Exploratory Data Analysis](#Exploratory-Data-Analysis)
4. [Data Modelling](#Data-Modelling)
5. [Contact](#Contact)
6. [Acknowledgements](#Acknowledgement)


Link to Raw memes in google drive-
https://drive.google.com/drive/folders/1QCbkMCfQGm1_-kYKil7LdJ1Hzv932N0a?usp=sharing


## Data preparation:
[link](https://github.com/ARGULASAISURAJ/Meme-Classification/blob/main/Text-mining-Data-preparation-Final.ipynb)
--> The first section code is about extracting text, Objects and Labels from Google API using Google API Secured key. Merging the labelled data from annotators and raw prepared data. Twitter memes extraction code is in a file with name- **twitter_memes_extraction.ipynb**

The output labels,objects and text are in the CSV file -> Full_data.csv
Labeled memes taken into model consideration-> Final_df.csv

## Pre-processing:
[link](https://github.com/ARGULASAISURAJ/Meme-Classification/blob/main/Text_Analytics_Project_PreProcessing-Final.ipynb)
--> This is the file where we did text cleaning process from the Final_df.csv - the cleaned text output is in final_dataframe.csv, on which we performed Exploratory Data Analysis and Modelling.Various pre-processing techniques were used to solve OCR errors like word segmentation, Internet slang contractions, spelling correction using language models.

## Exploratory Data Analysis:
[link](https://github.com/ARGULASAISURAJ/Meme-Classification/blob/main/Text-mining-Data-Exploratory-Data-Analysis-Final.ipynb)
--> Conducted exploratory data analysis to understand the data(Used Topic modelling, word frequency plots, Named Entity Recognition using spacy language model, Bigrams & Trigrams to understand the conext of a meme). Used pre-trained fasttext model with urban dictionary embeddings to get better representations of internet slang words

## Data Modelling:
[link](https://github.com/ARGULASAISURAJ/Meme-Classification/blob/main/Text-mining-Data-Modelling-Final.ipynb)
--> File in which we did modelling on only text and built Multimodals on Text as well as Images. Built four models to check which type of model has outperformed others and can be used to improve the current algorithms

-->This file can be run on GPU in Google collab. This is facebook community pytorch implementation of prodcution ready code for Facebook AI research project. we made minor changes to this code, so that we can compare the performaceof our model with theirs.

Refer to Project document for- Insights from our current work and future possible work 

## Contact:

Please feel free to reachout to us for any help through LinkedIn:
[Ashrit Kulkarni](https://www.linkedin.com/in/ashrit-kulkarni/)
[Suraj Arugula](https://www.linkedin.com/in/sai-suraj-argula-47900089/)
[Nagarjuna Kanneganti](https://www.linkedin.com/in/nagarjuna-kanneganti-20ab218a/)

## Acknowledgements:

1. [Google API](https://cloud.google.com/vision/docs/drag-and-drop)
2. [Facebook AI Meme challenge](https://arxiv.org/pdf/2005.04790.pdf)
