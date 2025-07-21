# Data Analysis and Machine Learning Labs

This repository contains a collection of Python-based data analysis and machine learning projects. Each project is presented as a Jupyter Notebook and demonstrates various data processing and modeling techniques.

## Projects Included

### 1. Lab 09: Big Data Analysis with PySpark

This project demonstrates fundamental big data processing techniques using PySpark to analyze a social media engagement dataset.

* **Dataset**: `social_media_engagement.csv`
* **Key Techniques**:
    * Loading and inspecting data into a Spark DataFrame.
    * Filtering data based on conditions (e.g., posts with more than 500 likes).
    * Aggregating data using `groupBy` to calculate metrics like average likes per platform.
    * Performing DataFrame joins on a common key (`post_id`).
    * Visualizing data distribution using Matplotlib and Seaborn.

### 2. Lab 10: Customer Segmentation with Scikit-learn

This project focuses on customer segmentation using unsupervised machine learning algorithms from the Scikit-learn library to identify distinct customer groups.

* **Dataset**: `Customers.csv`
* **Key Techniques**:
    * Applying K-Means Clustering to group customers based on their income and spending habits.
    * Using the Elbow Method to determine the optimal number of clusters for K-Means.
    * Performing Agglomerative Hierarchical Clustering and visualizing the hierarchy with a dendrogram.
    * Feature scaling with `StandardScaler` to normalize the data before modeling.
    * Applying feature selection techniques like a Low-Variance Filter and a correlation heatmap.

## Technologies Used

* Python
* PySpark
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    ```
2.  **Install dependencies:**
    It is recommended to create a virtual environment and install the required libraries.
    ```bash
    pip install -r requirements.txt
    ```
    *(You will need to create a `requirements.txt` file for this.)*

3.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
4.  Navigate to the respective lab folder and open the `.ipynb` file to run the cells.
