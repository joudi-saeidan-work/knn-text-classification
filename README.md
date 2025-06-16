# Machine Learning - Text Classification (kNN Coursework)

This project was completed as part of my Machine Learning module at university.

## Lab Overview

Task: Implement and evaluate the k-Nearest Neighbors (k-NN) algorithm for text classification using a 4-class subset of the Reuters News dataset.

Topics covered:

- Text data classification using k-NN
- Comparison of Euclidean distance vs Cosine similarity
- Bias-variance tradeoff analysis for different k values
- Few-shot learning concepts
- Confidence interval estimation for model error

## Files

- `knn-text-classification.ipynb` — Jupyter notebook containing full code and experiments.
- `ml-report.pdf` — Lab report with full analysis and discussion.

## Dataset

The Reuters dataset used in this coursework is not included in this repository due to licensing restrictions.  
For more information: [Reuters-21578 Dataset (UCI ML Repository)](https://archive.ics.uci.edu/dataset/137/reuters+21578+text+categorization+collection)

## Dataset Preparation

This project assumes you have access to the Reuters News dataset, preprocessed into a sparse matrix format.

The file `ReutersNews_4Classes_sparse.npy` should contain:

- A sparse matrix representation of the text data (e.g., TF-IDF vectors)
- Only 4 selected classes from the full Reuters dataset

**Note:** This preprocessed dataset was provided as part of the university coursework and is not publicly distributed. To replicate this project, you will need to:

1. Download the full Reuters-21578 dataset from the UCI Machine Learning Repository:  
   https://archive.ics.uci.edu/dataset/137/reuters+21578+text+categorization+collection

2. Select the 4 target classes used in the coursework.

3. Vectorize the text data (e.g., using TF-IDF vectorization).

4. Convert the data into a sparse numpy array and save it as `ReutersNews_4Classes_sparse.npy`.

Due to licensing restrictions, this preprocessed dataset file is not included in this repository.

## Disclaimer

This repository contains coursework material submitted for academic purposes only.
