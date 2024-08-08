# Sentiment Analysis Project

## Project Summary
This project is part of a fellowship application coding challenge. The goal is to perform sentiment analysis on the IMDB Dataset of 50K Movie Reviews. The dataset is used to predict the sentiment (positive or negative) of movie reviews using either classification or deep learning algorithms.

## About the Dataset
The IMDB dataset contains 50,000 movie reviews for natural language processing or text analytics. This dataset is designed for binary sentiment classification and includes:

- 25,000 highly polarized movie reviews for training
- 25,000 reviews for testing

The dataset file is located in the `data` folder of this project and is named `IMDB Dataset.csv`.

## Installation

To run this project, you'll need to install the dependencies listed in the `requirements.txt` file. Follow these steps to set up your environment:

1. **Clone the Repository**
    - git clone https://github.com/i4seeu/sentiment-analysis.git or git clone git@github.com:i4seeu/sentiment-analysis.git or gh repo clone i4seeu/sentiment-analysis
    - cd sentiment-analysis

2. **Set Up a Virtual Environment (Optional but Recommended)**
    - python -m venv venv
    - source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. **Install Dependencies**
    - pip install -r requirements.txt

**Data Location**
The dataset is located in the data folder within the project directory:
File: data/IMDB Dataset.csv

**Usage**

After installing the dependencies, you can run the sentiment analysis notebook script. Ensure that the dataset file IMDB Dataset.csv is placed in the data folder. Follow the instructions in the script to preprocess the data and train the model.