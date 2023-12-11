# Hate Speech Detection Project

## Overview

This project focuses on detecting hate speech in textual data using machine learning techniques. The dataset used for training is from the [hate_speech_dataset] in CSV format. The primary goal is to build a model capable of identifying hateful content in comments.

## Model Performance

Below are the precision, recall, and F1 score metrics for each algorithm on the test dataset:

| Algorithm            | Data  | Precision | Recall | F1 Score |
|----------------------|-------|-----------|--------|----------|  
| Random Forest        | Text  | 0.916     | 0.402  | 0.560    |
| Logistic Regression  | Text  | 0.87      | 0.696  | 0.773    |
| k-NN                 | Text  | 0.897     | 0.182  | 0.302    |
| Decision Tree        | Text  | 0.714     | 0.669  | 0.691    |

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

## License

This project is licensed under the [MIT License](LICENSE).
