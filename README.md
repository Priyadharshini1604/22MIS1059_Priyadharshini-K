# 22MIS1059_Priyadharshini-K
Application of Neural Networks _ Self Organizing Map 

Abstract
This study uses a Self-Organizing Map (SOM) to conduct consumer segmentation on an online retail dataset. The SOM, an unsupervised neural network, groups customers based on their purchase behavior, allowing firms to discover distinct client segments. The dataset had been processed and standardized before being trained to map multidimensional data to a 2D grid using the SOM. Each consumer was allocated to a "winning" neuron, which organized them into clusters. The project includes a display of the SOM distance map, segment results, a file that can be executed, and a README that has extensive instructions for running the implementation

About the Dataset
Dataset Name: Online Retail Dataset
Source: Available on Kaggle

Description: This dataset contains transactional data from a UK-based online retailer from 2010-2011. The key columns used in this analysis include:
CustomerID: Unique identifier for each customer
Quantity: The number of items purchased per transaction
UnitPrice: The price per item in the transaction
InvoiceNo: Invoice number representing the transaction
InvoiceDate: Date of the transaction

Output
The output of this project includes:

Customer Segmentation Results: A CSV file (Customer_Segmentation_Results.csv) containing the customer IDs and their respective cluster labels, which are determined by the SOM.
Visualization: A distance map (U-matrix) generated from the SOM, which helps visualize the customer clusters and how distinct or similar the clusters are.
How to Execute

Software Requirements
Python Version: 3.x
Required Libraries:
pandas
numpy
matplotlib
sklearn (for scaling)
minisom (for the Self-Organizing Map algorithm)
Installation
You can install the required libraries using pip:
pip install pandas numpy matplotlib scikit-learn minisom

Hardware Requirements
Minimum Hardware: Standard PC or laptop with 4 GB of RAM
Cloud Option: The project can also be executed using cloud platforms such as Google Colab.

Steps to Execute
Clone or Download the Repository: Clone the GitHub repository or download the files:
Upload Dataset: If you're working locally, make sure to place the dataset (Online_Retail.csv) into the appropriate directory or upload it into Google Colab.

Open the Google collab

Open the SOM_Customer_Segmentation.ipynb in Google Colab.
Run the cells sequentially.
Run the Code:

The SOM is trained using customer purchase behavior (i.e., Quantity and UnitPrice).
Visualizations, such as the distance map, will help you explore how customers are clustered.

Download Results:
After executing the notebook, the segmented customer data is saved into a CSV file (Customer_Segmentation_Results.csv).
