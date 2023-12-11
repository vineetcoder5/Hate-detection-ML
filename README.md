# Hate-detection-ML

# Hate Speech Detection Project

## Overview

This project focuses on detecting hate speech in textual data using machine learning techniques. The dataset used for training is from the [hate_speech_dataset](https://colab.research.google.com/drive/1zNMioIM5ClhR2ABcEneuvYPAFDSiFuW7) in CSV format. The primary goal is to build a model capable of identifying hateful content in comments.

## Project Structure

- `test.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `countvector_1.pkl`: Model checkpoint file saved using the joblib library.
- `hate_speech_dataset/train.csv`: Dataset file containing the labeled comments.

## Usage

1. Open the `test.ipynb` notebook using a Jupyter environment.
2. Connect to Google Drive to access the dataset.
3. Execute the notebook cells step by step to load the data, preprocess it, train the model, and evaluate its performance.
4. The trained model is saved as `countvector_1.pkl` for future use.

## Dependencies

- pandas
- numpy
- scikit-learn
- joblib
- Google Colab (for notebook execution)

