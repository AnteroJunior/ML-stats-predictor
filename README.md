# ML Stats Predictor

This Machine Learning model is trained to predict Facebook statistics about likes, comments, and sharing according the user answers to some questions.

## Description

This project uses a Linear Regression model to predict Facebook engagement metrics based on features like media type, post month, day of week, post hour, and whether the post is paid.

The model was trained on a dataset that was cleaned and preprocessed using Pandas and Scikit-learn.

## Usage

To use the model, simply run the code in a Google Colab notebook or Jupyter Notebook. The code will prompt you to enter the following information:

* Media type (Photo, Link, Status, or Video)
* Post month (0-11, where 0 is January)
* Day of week (1-7, where 1 is Monday)
* Post hour (0-23)
* Is the post paid? (0 for No, 1 for Yes)


The model will then output the predicted number of likes, shares, and comments.
