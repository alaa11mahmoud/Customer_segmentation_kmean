📈## Project Title: Customer Segmentation Using K-Means Clustering

### Description

This project implements K-Means clustering to analyze and segment mall customers based on their annual income and spending scores. The aim is to uncover meaningful patterns in customer behavior, allowing for targeted marketing strategies.

### Key Features

- **Data Source:** The dataset consists of various customer attributes, focusing on annual income and spending scores.
  
- **Data Processing:**
  1. **Data Reading:** Load the dataset using Pandas.
  2. **Data Cleaning:** Handle missing values and ensure data integrity.
  
- **Exploratory Data Analysis (EDA):**
  - Visualize the relationship between annual income and spending scores to detect patterns and trends.

- **Clustering:** Utilizes the K-Means algorithm to segment customers into 5 distinct clusters:
  1. **Low Income, High Spending**
  2. **Low Income, Low Spending**
  3. **High Income, High Spending**
  4. **High Income, Low Spending**
  5. **Middle Income, Middle Spending**

- **Elbow Method:** Employed to determine the optimal number of clusters, providing a visual representation of variance explained by each cluster.

### Objectives

- To identify customer segments that can inform marketing strategies.
- To enhance understanding of customer behaviors and preferences based on income and spending metrics.

###Technologies Used

- Python, Pandas, NumPy
- Sklearn for machine learning
- Matplotlib and Seaborn for data visualization

💻How to Run

1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter Notebook to execute the data reading, cleaning, EDA, and clustering analysis.

📊Conclusion

By segmenting customers based on income and spending behavior, businesses can tailor their marketing strategies to better meet the needs of each segment, ultimately driving engagement and sales.
