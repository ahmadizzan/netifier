# Netifier

Introduction
------------------
The rapid spread of information through internet have benefitted our lives in many different ways. But, it also introduces us to some problems, one of them being the spead of negative contents on the internet. The presence of 'toxic' post led to peopple struggle to have effective conversations.

Inspired by [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge), we decided to do similar thing using data from Indonesian social media. Our goal is to analyze and create multi-label text toxicity classifier using machine learning.


Contributions
------------------
1. Created Indonesian Social Media Text Toxicity Dataset
2. Created Pipeline For The Task: Exploratory Data Analysis, Data Preprocessing, and Modelling
3. Compared Various Machine Learning Model Performance On This Task


Dataset
------------------
As far as we know, there's no available public dataset on Indonesian text toxicity and we decided to collect the data ourselves. We scraped posts on famous social media sites in Indonesia, such as Instagram, Twitter, and Kaskus. We then manually labelled ~7000 samples into 4 categories: pornography, hate speech, racism, and radicalism.

We also attempted to collect more data using semi-supervised method. We collected additional ~20.000 samples through this method. All of the data could be downloaded from this repository.


Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    └── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
     						  and short description


Contributors
------------
- Ahmad Izzan
- Christian Wibisono
- Ilham Firdausi Putra