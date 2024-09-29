# SOM Clustering on Red Wine Quality Dataset

## Overview
This project demonstrates how to use **Self-Organizing Maps (SOM)** to cluster wines from the **Wine Quality Dataset** based on their chemical features. The goal is to group wines into clusters and visualize their relationships.

## Dataset
The **Wine Quality Dataset** includes chemical properties of red wines with a target quality score between 0 and 10. The dataset contains features like:
- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`, etc.

Dataset link: [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

## Software Requirements
To run this project, ensure you have the following software installed:

- **Python**: Version 3.6 or higher
- **Libraries**: The following Python libraries are required:
  - `pandas`
  - `matplotlib`
  - `minisom`
  - `scikit-learn`

## Hardware Requirements

-  **Processor**: Minimum Intel i3 or equivalent
-**RAM**: At least 4 GB
- **Disk Space**: Minimum 500 MB of free space for Python and library installations

## Run in order
 - **python wine_quality_segmentation.py**
 - **python uplot_umatrix.py**
 - **python uplot2_umatrix.py**
 - **python plot_bar_graphss.py**

## Prerequisites
Before running the code, ensure you have the following libraries installed:
```bash
pip install pandas matplotlib minisom scikit-learn


## Instructions
1. Clone the repository
https://github.com/trivikram-06/Red-Wine-Quality.git
cd SOM-Wine-Clustering

## 2. Run the Python Scripts
1. Train the SOM and Save Cluster Data
This script trains the SOM on the wine dataset and saves the cluster data in a CSV file
python wine_quality_segmentation.py

##3. Generate U-Matrix Heatmap
This script generates and saves the U-Matrix heatmap, which shows the distances between neurons.
python uplot_umatrix.py

##4. Visualize Clusters with Markers
This script visualizes the SOM clusters with different markers based on the wine quality.
python uplot2_umatrix.py

##5. Plot Average Wine Quality by Cluster
This script creates a bar chart of the average wine quality for each cluster.
python plot_bar_graphss.py


