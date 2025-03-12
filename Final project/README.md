# KMeans-Based Undersampling for Imbalanced Data

## Overview

This project explores the use of KMeans-based undersampling to address class imbalance in machine learning datasets. The goal is to improve model performance by reducing the dominance of majority-class samples while preserving the overall structure of the dataset. The project includes a Jupyter Notebook (Colab) implementation, demonstrating the effectiveness of this approach on a real-world dataset.

## Motivation

Class imbalance is a common issue in many classification problems, especially in medical datasets. Traditional resampling methods like random undersampling can lead to loss of valuable information, while oversampling methods may introduce redundancy. Our approach leverages KMeans clustering to selectively remove redundant samples while maintaining diversity within the minority class.

## Methodology

### Data Preprocessing:

* Load and clean the dataset.

* Identify class imbalance.

* KMeans-Based Undersampling:

* Apply KMeans clustering to the majority class.

* Select representative samples from each cluster to retain diversity.

* Balance the dataset by combining the sampled majority class with the minority class.

### Model Training & Evaluation:

Train machine learning models on the original and resampled datasets.

Compare performance metrics (AUC, F1-score, Recall, Precision, etc.).

## Installation

To run this project, clone the repository and install the required dependencies:

```git clone https://github.com/tamarmic/Tabular-data-science.git```

```cd Final project```

```pip install -r requirements.txt```

## Files

* TDS_clustering_all_datasets_final.ipynb: Main notebook implementing the approach.

* data/: Folder containing sample datasets.

* README.md: This documentation.

* TDS_Project.pdf: Explains and summarizes the method and all results

## The method was tested on an imbalanced dataset.

The balanced dataset improved model performance, especially in recall and F1-score.

The approach preserved meaningful patterns in the data while reducing bias towards the majority class.

## Contributors

Devora Siminovsky and Tamar Michelson
