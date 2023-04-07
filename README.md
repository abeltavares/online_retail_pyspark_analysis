[![PySpark](https://img.shields.io/badge/PySpark-3.3.2-orange.svg)](https://spark.apache.org/docs/latest/api/python/index.html)

# Online Retail Data Analysis

This repository contains an analysis of the Online Retail dataset, which includes transactional data from a UK-based online retailer. The analysis is performed using PySpark in Jupyter Notebooks.

## Dataset

The dataset used in this analysis can be found in the `data` folder. The dataset contains information about customer purchases, including product descriptions, quantities, and prices.

## Notebooks

The analysis is divided into several Jupyter Notebooks, each focusing on a specific aspect of the data:

- `Exploratory_Data_Analysis.ipynb`: Exploratory data analysis to understand the structure and distribution of the data.
- `RFM_Analysis.ipynb`: RFM analysis to segment customers based on their purchasing behavior.
- `KMeans_Clustering.ipynb`: K-means clustering to segment customers based on their order history.
- `Product_Affinity_Analysis.ipynb`: Product affinity analysis to identify which products tend to be purchased together.
- `Market_Basket_Analysis.ipynb`: Market basket analysis to analyze which products tend to be purchased together at different times of day, week, or year.
- `Churn_Analysis.ipynb`: Churn analysis to identify customers who are likely to churn based on their past behavior.

## Requirements

The analysis requires PySpark and Jupyter Notebook. The necessary Python libraries can be installed using the `requirements.txt` file.

## Usage

To run the analysis, clone the repository and open the Jupyter Notebooks in order.

## Contributions

This project is open to contributions. If you have any suggestions or improvements, please feel free to create a pull request.

## Copyright
© 2023 Abel Tavares
