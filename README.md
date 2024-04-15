# Jaydh9121-M11_CryptoClustering
# Cryptocurrency Clustering Project

## Introduction
This project involves clustering cryptocurrencies based on their market data using K-means clustering and Principal Component Analysis (PCA). The goal is to identify patterns and group similar cryptocurrencies together.

## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib
- hvPlot

## Installation
1. Clone this repository to your local machine.
2. Install the required Python libraries mentioned in the `requirements.txt` file using pip:
   ```bash
   
   ## Usage
1. Open the Jupyter Notebook file `crypto_clustering.ipynb`.
2. Follow the step-by-step instructions in the notebook to perform clustering on cryptocurrency market data.
3. Run each cell in the notebook to execute the code and observe the results.

## Contents
- Importing required libraries and dependencies.
- Loading and preprocessing cryptocurrency market data.
- Exploratory data analysis (EDA) including summary statistics.
- Normalizing the data using `StandardScaler`.
- Clustering cryptocurrencies with K-means using the original scaled data.
- Finding the optimal value for k using the Elbow method.
- Clustering cryptocurrencies with K-means using PCA data.
- Visualizing clusters using scatter plots.
- Determining the weights of each feature on each principal component.

## Results
- The best value for k determined using the Elbow method was 4, both with the original scaled data and PCA data.
- Cryptocurrencies were successfully clustered into 4 groups based on their market data.
- Scatter plots were created to visualize the clusters in both original and PCA dimensions.
- Principal components analysis revealed the features with the strongest positive and negative influences on each component.

## Conclusion
This project demonstrates how to apply K-means clustering and PCA to analyze and cluster cryptocurrency market data. The identified clusters can be further analyzed for insights into market trends and behavior.

## Sources

- **Python**: Used as the primary programming language for this project.
- **Command-line interface (CLI) or Graphical user interface (GUI)**: Depending on the application design, either a CLI or GUI was employed.
- **Contribution**: Code used in this project was referenced from prior modules, ChatGPT, Copilot, and various Google searches to help understand syntax and correct errors.

