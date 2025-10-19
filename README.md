# Sentiment Analysis of IMDB Movie Reviews using an LSTM Network

## Overview

This project classifies movie reviews from the IMDB dataset as either **positive** or **negative** using a Long Short-Term Memory (LSTM) neural network.

## Model Architecture

The model uses a sequential Keras architecture:
1.  **Embedding Layer**: Converts text into dense 128-dimension vectors.
2.  **LSTM Layer**: Processes the sequence of vectors to capture context.
3.  **Dense Layer**: The final output layer with a **sigmoid activation** to produce a probability score.

## How to Run This Project

1.  Clone the repository.
2.  Create a virtual environment.
3.  Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
4.  Launch the Jupyter Notebook:
    ```bash
    jupyter notebook sentiment_analysis.ipynb
    ```

## Results

The model achieved an accuracy of **85%** on the test set.

## Contributors

* **Shiwangee Ghosh** - [Link to your GitHub profile later]
* **Mahima Paithankar** - [Link to your partner's GitHub profile later]
