# 🛍️ Product Segmentation using K-Means Clustering

This project performs customer product segmentation using unsupervised machine learning (K-Means Clustering). The goal is to group similar products based on features like price, discounts, ratings, and reviews — helping businesses better understand product categories and pricing strategies.

## 📁 Dataset

The dataset contains product-related features:
- Product Name
- Listing Price
- Sale Price
- Discount
- Brand
- Rating
- Reviews

## 🚀 Key Steps

- **Data Cleaning**: Removed duplicates, handled missing values, and fixed zero pricing issues.
- **Feature Scaling**: Applied `StandardScaler` to normalize numerical values.
- **Clustering**: Used the K-Means algorithm to segment products into similar clusters.
- **Evaluation**:
  - Elbow Method for optimal k
  - Silhouette Score for quality check
- **Visualization**:
  - Boxplots and pairplots to analyze variable distribution
  - Cluster profiling for meaningful interpretation

## 📊 Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Yellowbrick (for visual clustering diagnostics)

## 📌 Output

- Products segmented into 4 clusters.
- Profiles for each cluster showing average price, discount, rating, and review count.
- Visual plots to help interpret clustering quality and feature impact.

## 📂 Notebook

All code and analysis are documented in:  
[`CaseStudy_ProductSegmentation.ipynb`](CaseStudy_ProductSegmentation.ipynb)

## ✅ How to Run

```bash
pip install -r requirements.txt
jupyter notebook CaseStudy_ProductSegmentation.ipynb


📬 Contact

Let me know if you want to include a `requirements.txt` file or want a more advanced section like deployment or business insights!
