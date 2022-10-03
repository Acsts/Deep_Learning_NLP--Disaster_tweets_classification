# Disaster tweets classification project

## Jedha Fullstack Certification
- email : antoine.costes@live.fr
- Video link : https://share.vidyard.com/watch/U6gDKzuE41QC1ZRB2LiHTv?

## Goal of the project

The goal of this project is to predict if a tweet is disaster-related or not (binary classification problem).
The project is based on a closed Kaggle competition [available here](https://www.kaggle.com/c/nlp-getting-started).

## Datasets

The train and test dataset provided for this project are available on Kaggle [here](https://www.kaggle.com/c/nlp-getting-started) and have been copied in the 'input_data' folder of this repository.
The training of the model is made on the 'train' dataset (labeled) and the submissions are made for the 'test' (not labeled) dataset.
The predictions submissions made by my model are stored in the file 'submission.csv'.

## Getting started - Prerequisites

1. Clone this repository to create your project folder :
    ```sh
    git clone https://github.com/Acsts/Deep_Learning_NLP--Disaster_tweets_classification.git
    ```

2. Installations : 

    All the source code is written in Python3. 
    The dependencies you need to run the code are listed in the 'requirements.txt' file, you can install them with pip by running 

    ```sh
    pip install -r requirements.txt
    ```
    _Note : if you want to run the notebook in Google Colab environment, you don't need all these installations. You will just need to install kaleido for plotly visualizations (by running the first cell of the notebook). 

## Usage

The plotly figures are shown by default in png format in order to appear correctly on github. 
If you want to take advantage of the interactive features of plotly figures, comment/delete the line `pio.renderers.default = "png"` and re-run the notebook.
