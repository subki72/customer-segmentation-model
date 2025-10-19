# Customer Segmentation using K-Means Clustering

### About The Project

This project presents a machine learning model for customer segmentation using the K-Means clustering algorithm. The model analyzes a dataset of bank customers to group them into distinct segments based on their demographic information, financial status, and product ownership.

The primary objective is to provide actionable insights that can help marketing teams develop targeted strategies, improve customer engagement, and optimize product offerings for each specific segment.

### Built With
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib & Seaborn
* Jupyter Notebook

### Dataset
The model is trained on the `clustering_data.csv` dataset, which contains anonymized customer information including area, age, vintage, product holdings, and annual income.

### Methodology
The project follows these key steps:
1.  **Data Preprocessing**: Cleaning the data, handling categorical features with One-Hot Encoding, and scaling numerical features using StandardScaler.
2.  **Feature Selection**: Removing highly correlated features to prevent multicollinearity and improve model performance.
3.  **Model Training**: Implementing the K-Means algorithm and determining the optimal number of clusters using the Elbow Method.
4.  **Evaluation**: Validating the clustering results with the Silhouette Score.
5.  **Cluster Analysis**: Interpreting the characteristics of each customer segment to build distinct personas.

### How to Run
1. Clone this repository to your local machine.
2. Ensure you have all the required libraries installed from the list above.
3. Open `Clustering_Model.ipynb` in Jupyter Notebook and run the cells sequentially.
