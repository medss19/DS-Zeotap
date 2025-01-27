# eCommerce Customer Analysis

## **Overview**

This project performs a comprehensive analysis of an eCommerce transactions dataset. The analysis is divided into three main tasks:

1. **Exploratory Data Analysis (EDA)**: 
   Key insights are derived from customer demographics, product preferences, and transaction patterns.

2. **Lookalike Model**:
   A machine learning model is developed to recommend similar customers based on their profiles and transaction histories.

3. **Customer Segmentation**:
   Customers are grouped into distinct clusters using clustering techniques for targeted marketing and personalized strategies.

---

## **Dataset**

The analysis uses the following datasets:

1. **Customers.csv**:
   - Customer profiles, including demographic data.
2. **Transactions.csv**:
   - Historical transaction details.
3. **Products.csv**:
   - Product information.

---

## **Tasks**

### **Task 1: Exploratory Data Analysis (EDA)**

- **Objective**: Extract key business insights.
- **Deliverables**:
  - Customer distribution by region.
  - Analysis of sign-up trends over the years.
  - Identification of top products.
  - Price distribution analysis.
  - Top 10 high-value transactions.

### **Task 2: Lookalike Model**

- **Objective**: Recommend 3 similar customers for a given user.
- **Methodology**:
  - Feature engineering on customer profiles and transaction data.
  - Similarity calculation using cosine similarity.
- **Deliverables**:
  - A "Lookalike.csv" file mapping each customer to their top 3 similar customers with similarity scores.
  - A Python script or Jupyter notebook explaining the model logic.

### **Task 3: Customer Segmentation**

- **Objective**: Segment customers into meaningful clusters.
- **Methodology**:
  - Clustering techniques (e.g., KMeans) applied to profile and transaction data.
  - Evaluation using Davies-Bouldin Index and Silhouette Score.
- **Deliverables**:
  - A report detailing the number of clusters, DB Index, and other metrics.
  - Visual representation of clusters using PCA.
  - A Python script or Jupyter notebook.

---

## **Project Deliverables**

1. **Code**:
   - Python scripts or Jupyter notebooks for each task.
   
2. **Reports**:
   - Detailed insights from EDA.
   - Clustering report with metrics and visualizations.
   
3. **Files**:
   - "Lookalike.csv" for Task 2.
   - Data preprocessing and cleaning steps included in scripts.

---

## **Installation and Usage**

### **Requirements**
- Python (>=3.8)
- Required Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

### **Steps to Run**
1. Clone this repository.
2. Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the respective scripts for each task:
   - `Medha_Agarwal_EDA.ipynb` for exploratory data analysis.
   - `Medha_Agarwal_Lookalike.ipynb` for the lookalike recommendation system.
   - `Medha_Agarwal_Clustering.ipynb` for clustering analysis.

---

## **Results**

- **EDA**:
  Key insights into customer behavior, product preferences, and transaction trends.
- **Lookalike Model**:
  Recommendations for similar customers based on profiles and transaction history.
- **Customer Segmentation**:
  Formation of 5 clusters with a Davies-Bouldin Index of 1.1169, indicating well-defined groupings.

---
