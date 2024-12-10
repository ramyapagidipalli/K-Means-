# Customer Segmentation using K-Means Clustering

## Overview
This project applies **K-Means Clustering**, an unsupervised machine learning technique, to segment customers based on their **Annual Income** and **Spending Score**. By identifying distinct customer groups, businesses can develop targeted marketing strategies and optimize resource allocation.


---

## Dataset Description
The dataset contains **200 customer records** with the following attributes:
- `CustomerID`: Unique identifier for each customer (not used for clustering).
- `Gender`: Male or Female (encoded numerically for clustering).
- `Age`: Customer's age.
- `Annual Income`: Customer's annual income in thousands of dollars.
- `Spending Score`: A score (1-100) reflecting customer spending habits.

For clustering, **Annual Income** and **Spending Score** were chosen as features.

---

## Methodology
1. **Preprocessing**: Data normalization and encoding for gender.
2. **Optimal Number of Clusters**:
   - **Elbow Method**: Determined \(k=4\) based on the "elbow point."
   - **Silhouette Analysis**: Verified that \(k=4\) provided the best balance of cohesion and separation.
3. **Initialization Methods**:
   - Compared **Random Initialization** vs **K-Means++ Initialization**.
   - **K-Means++** was found to be superior due to faster convergence and better cluster quality.
4. **Clustering**: Applied K-Means with \(k=4\) to group customers into 4 distinct clusters.

---

## Evaluation Metrics
- **Within-Cluster Sum of Squares (WCSS)**: Measures intra-cluster variance, minimized during clustering.
- **Silhouette Score**: Assesses cluster quality by comparing cohesion and separation. Average score = **0.41**.

---

## Key Insights
The 4 clusters identified represent:
1. **High Income, High Spending**: Ideal customers for premium offers.
2. **Low Income, Low Spending**: Customers with limited engagement.
3. **High Income, Low Spending**: Potential customers needing targeted strategies.
4. **Low Income, High Spending**: Price-conscious but loyal customers.

---

## Conclusion
- \(k=4\) clusters provide the best segmentation for the dataset.
- **K-Means++ Initialization** outperforms random initialization, delivering better-defined clusters and faster convergence.
- The clustering insights can support personalized marketing strategies and customer profiling.

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/kmeans-customer-segmentation.git
   cd kmeans-customer-segmentation
# Customer Segmentation using K-Means Clustering

## Overview
This project applies **K-Means Clustering**, an unsupervised machine learning technique, to segment customers based on their **Annual Income** and **Spending Score**. By identifying distinct customer groups, businesses can develop targeted marketing strategies and optimize resource allocation.

---

## Table of Contents
1. [Dataset Description](#dataset-description)
2. [Methodology](#methodology)
3. [Evaluation Metrics](#evaluation-metrics)
4. [Key Insights](#key-insights)
5. [Conclusion](#conclusion)
6. [Usage](#usage)

---

## Dataset Description
The dataset contains **200 customer records** with the following attributes:
- `CustomerID`: Unique identifier for each customer (not used for clustering).
- `Gender`: Male or Female (encoded numerically for clustering).
- `Age`: Customer's age.
- `Annual Income`: Customer's annual income in thousands of dollars.
- `Spending Score`: A score (1-100) reflecting customer spending habits.

For clustering, **Annual Income** and **Spending Score** were chosen as features.

---

## Methodology
1. **Preprocessing**: Data normalization and encoding for gender.
2. **Optimal Number of Clusters**:
   - **Elbow Method**: Determined \(k=4\) based on the "elbow point."
   - **Silhouette Analysis**: Verified that \(k=4\) provided the best balance of cohesion and separation.
3. **Initialization Methods**:
   - Compared **Random Initialization** vs **K-Means++ Initialization**.
   - **K-Means++** was found to be superior due to faster convergence and better cluster quality.
4. **Clustering**: Applied K-Means with \(k=4\) to group customers into 4 distinct clusters.

---

## Evaluation Metrics
- **Within-Cluster Sum of Squares (WCSS)**: Measures intra-cluster variance, minimized during clustering.
- **Silhouette Score**: Assesses cluster quality by comparing cohesion and separation. Average score = **0.41**.

---

## Key Insights
The 4 clusters identified represent:
1. **High Income, High Spending**: Ideal customers for premium offers.
2. **Low Income, Low Spending**: Customers with limited engagement.
3. **High Income, Low Spending**: Potential customers needing targeted strategies.
4. **Low Income, High Spending**: Price-conscious but loyal customers.

---

## Conclusion
- \(k=4\) clusters provide the best segmentation for the dataset.
- **K-Means++ Initialization** outperforms random initialization, delivering better-defined clusters and faster convergence.
- The clustering insights can support personalized marketing strategies and customer profiling.

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/kmeans-customer-segmentation.git
   cd kmeans-customer-segmentation
# Customer Segmentation using K-Means Clustering

## Overview
This project applies **K-Means Clustering**, an unsupervised machine learning technique, to segment customers based on their **Annual Income** and **Spending Score**. By identifying distinct customer groups, businesses can develop targeted marketing strategies and optimize resource allocation.

---

## Table of Contents
1. [Dataset Description](#dataset-description)
2. [Methodology](#methodology)
3. [Evaluation Metrics](#evaluation-metrics)
4. [Key Insights](#key-insights)
5. [Conclusion](#conclusion)
6. [Usage](#usage)

---

## Dataset Description
The dataset contains **200 customer records** with the following attributes:
- `CustomerID`: Unique identifier for each customer (not used for clustering).
- `Gender`: Male or Female (encoded numerically for clustering).
- `Age`: Customer's age.
- `Annual Income`: Customer's annual income in thousands of dollars.
- `Spending Score`: A score (1-100) reflecting customer spending habits.

For clustering, **Annual Income** and **Spending Score** were chosen as features.

---

## Methodology
1. **Preprocessing**: Data normalization and encoding for gender.
2. **Optimal Number of Clusters**:
   - **Elbow Method**: Determined \(k=4\) based on the "elbow point."
   - **Silhouette Analysis**: Verified that \(k=4\) provided the best balance of cohesion and separation.
3. **Initialization Methods**:
   - Compared **Random Initialization** vs **K-Means++ Initialization**.
   - **K-Means++** was found to be superior due to faster convergence and better cluster quality.
4. **Clustering**: Applied K-Means with \(k=4\) to group customers into 4 distinct clusters.

---

## Evaluation Metrics
- **Within-Cluster Sum of Squares (WCSS)**: Measures intra-cluster variance, minimized during clustering.
- **Silhouette Score**: Assesses cluster quality by comparing cohesion and separation. Average score = **0.41**.

---

## Key Insights
The 4 clusters identified represent:
1. **High Income, High Spending**: Ideal customers for premium offers.
2. **Low Income, Low Spending**: Customers with limited engagement.
3. **High Income, Low Spending**: Potential customers needing targeted strategies.
4. **Low Income, High Spending**: Price-conscious but loyal customers.

---

## Conclusion
- \(k=4\) clusters provide the best segmentation for the dataset.
- **K-Means++ Initialization** outperforms random initialization, delivering better-defined clusters and faster convergence.
- The clustering insights can support personalized marketing strategies and customer profiling.

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/kmeans-customer-segmentation.git
   cd kmeans-customer-segmentation
2. instal necessary dependencies:
3.        pip install -r requirements.txt
4. Run the analysys script:
5.        python customer_segmentation.py
6. Visualize the clusters and evaluation metrics through the generated plots.

   Acknowledgments
This project demonstrates the application of machine learning for practical business use cases, particularly customer segmentation. The dataset was used solely for educational purposes.

Feel free to customize the repository name, scripts, or any other project-specific details.
