# Prodigy_ML_02  
## Customer Segmentation Using K-Means Clustering

## Overview
This project implements a K-Means clustering algorithm to group customers of a retail store based on their purchase behavior.

The clustering is performed using the Mall Customers Dataset from Kaggle, which includes customer details such as annual income and spending score.

## Problem Statement
To divide customers into different clusters based on their Annual Income and Spending Score using unsupervised machine learning (K-Means clustering).

## Algorithm Used
- K-Means Clustering
- Elbow Method to determine the optimal number of clusters

## Requirements
### Python Version
- Python 3.x

### Libraries Required
- pandas
- numpy
- matplotlib
- scikit-learn

## Installation / Implementation
### Option 1: Local Machine
Install the required libraries using:
pip install -r requirements.txt

### Option 2: Google Colab
You can run the project directly on Google Colab without installing any libraries locally.

## Dataset
1. Register or log in to Kaggle
2. Download the dataset Mall_Customers.csv from:
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
3. Place the downloaded file in the project directory

## Features Used for Clustering
- Annual Income (k$)
- Spending Score (1–100)

## Usage
Run the Jupyter Notebook:
Customer_Segmentation_KMeans.ipynb

## Steps Performed
1. Load and explore the dataset
2. Select relevant features
3. Apply feature scaling
4. Use Elbow Method
5. Train K-Means model
6. Assign cluster labels
7. Visualize customer segments

## Output / Results
Customers are grouped into 5 distinct clusters representing different spending behaviors.

## File Descriptions
- Customer_Segmentation_KMeans.ipynb – Complete implementation
- Mall_Customers.csv – Dataset
- README.md – Project documentation

## Conclusion
K-Means clustering helps in understanding customer behavior and enables targeted marketing strategies.
