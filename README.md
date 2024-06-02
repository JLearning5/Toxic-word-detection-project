# Toxic Word Detection Project

This project is designed to detect hate speech, offensive language, and neutral tweets using a machine learning model. The model is trained using a dataset of tweets, and the prediction is done using a Decision Tree classifier.

## Voilà

You can run this project interactively in your browser via Voilà by clicking the badge below:

[![Launch Voilà](https://img.shields.io/badge/launch-Voilà-blue.svg)](https://mybinder.org/v2/gh/JLearning5/Credit-Card-Fraud-Detection-project/HEAD?urlpath=voila/render/notebooks/Fraud_Detection_preview.ipynb)

## Binder

You can run the notebooks in your browser via Binder by clicking the badge below:

[![Binder](https://notebooks.gesis.org/binder/jupyter/user/jlearning5-toxi-tection-project-2pqjdmsu/lab/tree/notebooks/Toxic_word_detection.ipynb
)

## Project Overview

- **Data Cleaning**: The tweets are cleaned to remove unwanted characters, URLs, and punctuation.
- **Text Vectorization**: The cleaned text data is converted into numerical features using `CountVectorizer`.
- **Model Training**: A Decision Tree classifier is trained on the processed data.
- **User Interface**: An interactive interface is created using `ipywidgets` for users to input text and get predictions.

## Setup Instructions

### Prerequisites

Ensure you have the following installed:
- Python 3.6 or higher
- Jupyter Notebook or Jupyter Lab
- Required Python packages (listed below)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/JLearning5/Credit-Card-Fraud-Detection-project.git
   cd Credit-Card-Fraud-Detection-project
