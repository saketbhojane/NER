# Entity Extraction Project Documentation

In this project I tried and compare two distinct approaches to Named Entity Recognition (NER): one using Logistic Regression and the other utilizing Transformer models. Below are the setup instructions and observations from our experiments.

## NER with Logistic Regression

### Overview

The provided notebook demonstrates the process of entity extraction using Logistic Regression. It outlines the steps required to preprocess data, train the model, and evaluate its performance on a test set.

### Setup Instructions

1. **Install Dependencies**: Before running the notebook, ensure that all necessary packages are installed. You can install the required packages using the following command:
    ```bash
    pip install -r requirements.txt
    ```
2. **Execution**: Run the notebook cells sequentially to train and evaluate the Logistic Regression model for entity extraction.
   
### Results

The Logistic Regression model achieved an F1-Score of 0.94, indicating a high level of precision and recall in identifying named entities.

## NER with Transformers

### Overview

Following the same procedural steps as with Logistic Regression, this part of the project employs Transformer models, specifically utilizing the `bert-base-uncased` model for entity extraction.

### Setup Instructions

1. **Environment Preparation**: Ensure all dependencies are installed as per the `requirements.txt` file.
2. **Model Setup**: Maintain the same folder structure as provided to correctly import the `bert-base-uncased` model.
3. **Execution**: Sequentially run the notebook cells to process the data, train the Transformer model, and evaluate its performance.

### Note

Both notebooks will definitely run smoothly as long as all dependencies and packages are correctly installed and the folder structure is maintained as instructed.

## Observations

Through the course of this project, it became evident that training Transformer models for NER tasks requires substantial computational resources and a significant amount of data. This is in contrast to Logistic Regression, which, while effective, leverages a simpler approach.
