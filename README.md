# SOM Clustering on Wine Quality Dataset

## Overview
This project demonstrates the use of **Self-Organizing Maps (SOM)** to cluster wines from the Wine Quality Dataset based on their chemical features. The goal is to group wines into clusters and visualize their relationships using various graphical outputs such as U-Matrix heatmaps, cluster markers, and average quality bar charts.

## Software Requirements
To run this project, ensure you have the following software installed:

- **Python**: Version 3.6 or higher
- **Libraries**: The following Python libraries are required:
  - `pandas`
  - `matplotlib`
  - `minisom`
  - `scikit-learn`

## Installation of Required Libraries
You can install the required libraries using `pip`. Open your terminal or command prompt and run the following command:

```bash
pip install pandas matplotlib minisom scikit-learn
Hardware Requirements
Processor: Minimum Intel i3 or equivalent
RAM: At least 4 GB
Disk Space: Minimum 500 MB of free space for Python and library installations
Instructions to Execute the Implementation
1. Clone the Repository
To clone the repository, open your terminal or command prompt and run the following command:

bash
Copy code
git clone https://github.com/your-username/SOM-Wine-Clustering.git
cd SOM-Wine-Clustering
2. Add the Dataset
Place the winequality-red.csv file into the project directory.

3. Run the Python Scripts
3.1 Train the SOM and Save Cluster Data
This script trains the SOM on the wine dataset and saves the cluster data into a CSV file.

bash
Copy code
python wine_quality_segmentation.py
Output: cluster_counts.csv
Description: The SOM is trained, and the wines are assigned to clusters based on their chemical properties.
3.2 Generate U-Matrix Heatmap
This script generates and saves the U-Matrix heatmap, visualizing the distances between neurons.

bash
Copy code
python uplot_umatrix.py
Output: u_matrix.png
Description: Visualizes the SOM distance map, highlighting potential cluster boundaries.
3.3 Visualize Clusters with Markers
This script visualizes the SOM clusters with different markers based on wine quality.

bash
Copy code
python uplot_umatrix.py
Output: Interactive plot
Description: Wines are plotted on the SOM grid, with different markers representing different clusters.
3.4 Plot Average Wine Quality by Cluster
This script generates a bar chart of the average wine quality for each cluster.

bash
Copy code
python plot_bar_graphss.py
Output: Interactive bar graph
Description: Displays the average quality of wines in each cluster, helping to identify patterns across the clusters.
