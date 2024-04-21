# Sentiment Analysis using Word2Vec and FastText

This repository contains code for sentiment analysis using Word2Vec and FastText models. The project aims to analyze movie reviews and classify them as positive or negative.

## Instructions

To execute the code, follow these steps:

1. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Execute the Jupyter Notebook `SE23MAID010_Assign3.ipynb`:

   ```bash
   jupyter notebook SE23MAID010_Assign3.ipynb
   ```

5. Follow the instructions and run each cell in the notebook to train the models, process the test data, and evaluate the results.

6. In the notebook, navigate to the 5th index of the Table of Contents titled "Building Word2Vec Model" and proceed with running the code cells from there.

## Implementation Details

- The code is implemented in Python using Jupyter Notebook.
- The models are trained using the Word2Vec and FastText algorithms.
- The `preprocess_text` function preprocesses the raw text data by tokenization, removing stopwords, and applying other text preprocessing techniques.
- The trained models are evaluated using metrics such as accuracy, precision, recall, and AUC.

## Directory Structure

- `data/`: Contains the raw data files.
- `models/`: Stores the trained Word2Vec and FastText models.

## Results

### Word2Vec Model

**Training Results:**
- Accuracy: 59.71%
- AUC: 63.16%
- Precision: 58.14%
- Recall: 74.48%

**Test Results:**
- Test Loss: 0.538
- Test Accuracy: 74.80%
- Test Precision: 69.27%
- Test Recall: 88.66%
- Test AUC: 89.14%

### FastText Model

**Training Results:**
- Accuracy: 99.88%
- AUC: 99.98%
- Precision: 99.89%
- Recall: 99.88%

**Test Results:**
- Test Loss: 0.829
- Test Accuracy: 84.87%
- Test Precision: 89.23%
- Test Recall: 84.19%
- Test AUC: 85.87%

## Analysis and Observations

- Both Word2Vec and FastText models are trained and evaluated.
- FastText shows slightly better performance in terms of accuracy and precision.
- FastText converges faster during training compared to Word2Vec.
- Adjustments to hyperparameters and model architecture may further improve performance.
