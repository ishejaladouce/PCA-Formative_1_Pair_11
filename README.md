# Principal Component Analysis (PCA): African Agriculture & Economic Development 

This repository contains a Jupyter Notebook implementing Principal Component Analysis (PCA) from scratch using Python and `numpy`. The analysis explores a dataset built from World Bank development indicators, tracking 54 African nations from 2000 to 2023.

## Overview & Notebook Pipeline

The notebook walks through a complete exploratory data analysis and dimensionality reduction workflow:

* **Data Acquisition & Cleaning:** Pulls 9 agricultural and macroeconomic indicators using the World Bank API (`wbgapi`), merges income-level metadata, and imputes missing values using column medians.


* **Standardization:** Scales features to a mean of 0 and standard deviation of 1 to prevent scale dominance.


* **Covariance Matrix & Eigendecomposition:** Computes the feature covariance matrix and performs eigendecomposition (`np.linalg.eigh`) to extract eigenvalues and eigenvectors.


* **Dimensionality Reduction:** Evaluates component selection using the Kaiser rule and a 90% cumulative variance threshold rule, projecting the dataset onto the top principal components.


* **Visualization:** Generates scree plots, comparative before-and-after PCA scatter plots grouped by country income levels, and feature loading inspections.



## Requirements

* Python 3.x
* `numpy`

* `pandas`

* `matplotlib`

* `wbgapi`

 By Becky and Ladouce
