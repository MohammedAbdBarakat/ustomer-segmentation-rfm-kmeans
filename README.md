# 🛍️ Customer Segmentation using RFM & K-Means

This project applies **RFM Analysis** (Recency, Frequency, Monetary) and **K-Means Clustering** to segment customers of an online retail store.  
The goal is to identify groups of customers based on purchasing behavior, which can help businesses with **personalized marketing, customer retention, and sales strategy**.

---

## 📊 Dataset

The dataset used is the **[Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)** from the UCI Machine Learning Repository (also available on [Kaggle](https://www.kaggle.com/datasets/lakshyaag/online-retail-dataset)).

- Transactions from a UK-based online retail company
- Period: **December 2010 – December 2011**
- ~500,000 rows and 8 features

⚠️ The full dataset (~44 MB) is not included in this repository.  
Instead, a **sample dataset with 1,000 rows** is provided (`sample_data.csv`) for demonstration.  
You can download the full dataset from the links above if you want to replicate the full analysis.

---

## 🛠️ Project Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Removing canceled transactions
   - Filtering valid customer IDs

2. **Feature Engineering**
   - RFM metrics calculation:
     - **Recency**: Days since last purchase  
     - **Frequency**: Number of transactions  
     - **Monetary**: Total spending  

3. **Clustering**
   - Standardization of RFM features
   - **K-Means clustering** to group customers
   - Choosing the optimal number of clusters (Elbow & Silhouette methods)

4. **Visualization**
   - Distribution of RFM metrics
   - Cluster profiles and insights

---

## 📂 Repository Structure

├── notebooks/ # Jupyter notebooks with analysis
├── sample_data.csv # Sample dataset (1,000 rows)
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── src/ # Source code (if modularized)

yaml
Copy
Edit

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/MohammedAbdBarakat/customer-segmentation-rfm-kmeans.git
   cd customer-segmentation-rfm-kmeans
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook
📈 Example Results
Customers are segmented into distinct groups (e.g., high-value, loyal, new, at-risk).

Visualizations provide insightful profiles for each cluster.

Helps businesses improve targeted marketing strategies.

📚 References
UCI Online Retail Dataset

Kaggle Dataset Version

Customer segmentation concepts: RFM Analysis

✨ Author
👤 Mohammed Abd Barakat
🔗 GitHub Profile