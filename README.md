# Problems of India: A Reddit Analysis

This project was done to identify the problems about India being talked about in social media. To this end, I have created a dataset of about 2000 posts discussing issues in India. When I say issues, I mean social problems. After collecting this dataset and performing pre-processing steps for clean up, I do an extensive exploratory data analysis of both numerical/categorical as well as textual features of the dataset. Finally, I train two baseline models for predicting a topic given the post text.

In case you want to play with the datasets or the models in the project, here is the [link](https://drive.google.com/drive/folders/1IJw0G_pGqixNzbG2_2_Ys0KFW9SkgYz2?usp=sharing)!

The project is divided into four parts:
1. Data Collection
2. Data Preprocessing
3. Exploratory data analysis
4. Baselining models for topic prediction

### [Data Collection](https://github.com/saum7800/india_problem_eda/blob/main/1_Data_Extract.ipynb)

I have described how I have procured the dataset in this [notebook](https://github.com/saum7800/india_problem_eda/blob/main/1_Data_Extract.ipynb). It is a combination of data from 2 subreddits: **r/India** and **r/IndiaSpeaks**. In case some parts of the notebook are not visible, here is the [colaboratory link](https://colab.research.google.com/drive/1_nYA17P86WAjZtdgplulTczMT60lHZAu?usp=sharing) for the same.

### [Data Preprocessing](https://github.com/saum7800/india_problem_eda/blob/main/2_Data_Preprocessing.ipynb)

This notebook cleans the collected data in multiple ways:
1. Merges the different data collected
2. Removes useless features
3. Fills in null values
4. cleans textual data and concatenates different texts

In case some parts of the notebook are not visible, here is the [colaboratory link](https://colab.research.google.com/drive/1-L6jf6FYZJXQnNCPHMFJFbui77xBlqtM?usp=sharing) for the same.

### [Exploratory Data Analysis](https://github.com/saum7800/india_problem_eda/blob/main/3_Exploratory_Data_Analysis.ipynb)

Once preprocessing is completed, we explore the data to find interesting nuances that we may not have expected and also reaffirm some expected outcomes. The notebook contains interactive plots in the result and is hence best viewed on colab itself [here](https://colab.research.google.com/drive/1RWcCZNKteIudU1dd0S6sYT7hFnn1QrMj?usp=sharing).

### [Baseline Predictors](https://github.com/saum7800/india_problem_eda/blob/main/4_Predictor_Model.ipynb)

I train two basic classifiers for this task. In case some parts of the notebook are not visible, here is the [colaboratory link](https://colab.research.google.com/drive/13Sz7X_0BNwhOZ97oo-bNZ--9bvVFGJ_k?usp=sharing)

1. Classical ML model: Multinomial Naive Bayes model
2. Neural ML model: Distilbert pre-trained

