This repository contains a Jupyter Notebook that performs data crawling and topic modeling on a dataset of tweets related to Raja Ampat, a popular tourist destination in Indonesia. The dataset includes tweets that mention Raja Ampat, and the goal of this project is to analyze the text data to uncover common themes or topics discussed by users on Twitter.

## Overview

The notebook includes the following steps:

1. **Data Loading**: The dataset is loaded from a CSV file containing tweets related to Raja Ampat.
2. **Data Preprocessing**:
   - **Case Folding**: Convert text to lowercase.
   - **Remove Hashtags**: Remove hashtags from the tweets.
   - **Remove URLs**: Remove any URLs present in the tweets.
   - **Remove Punctuation**: Remove punctuation marks from the text.
3. **Exploratory Data Analysis (EDA)**: Basic analysis of the dataset, including checking for duplicates and understanding the structure of the data.
4. **Topic Modeling**: The notebook will eventually include topic modeling techniques (e.g., Latent Dirichlet Allocation - LDA) to identify common topics in the tweets.

## Dataset

The dataset used in this project is a collection of tweets that mention Raja Ampat. The dataset includes various columns such as `full_text`, `created_at`, `tweet_url`, `username`, and more. The primary focus is on the `full_text` column, which contains the text of the tweets.
