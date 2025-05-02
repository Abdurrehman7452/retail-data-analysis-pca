# Retail Data Analysis & PCA Visualization

This project explores, preprocesses, and analyzes multiple retail and e-commerce datasets, focusing on data cleaning, feature engineering, and dimensionality reduction using Principal Component Analysis (PCA).

## 📊 Datasets Used

1. **Retail Transaction Dataset**  
   Source: [Kaggle](https://www.kaggle.com/datasets/fahadrehman07/retail-transaction-dataset)

2. **Online Retail Dataset**  
   Source: [UCI ML Repository](https://archive.ics.uci.edu/dataset/352/online+retail)

3. **E-commerce Search Relevance**  
   Source: [Data World](https://data.world/crowdflower/ecommerce-search-relevance)

---

## 🔧 Preprocessing Steps

- Filtered invalid data (e.g., negative prices)
- Renamed and standardized column names
- Added synthetic `TransactionDate` field
- Merged all datasets with consistent schema
- Handled missing values and corrected data types
- Detected and removed outliers using IQR method
- Created visualizations (boxplots, histograms)
- Engineered features like:
  - `TotalRevenue`
  - `PriceCategory`
  - `Month` and `SeasonName`
- Standardized numerical columns

---

## 📉 Principal Component Analysis (PCA)

- Applied PCA to reduce dimensionality
- Visualized the first two principal components (PC1 and PC2)
- Identified clusters and linear relationships
- Noted that 2111 components were needed to explain 95% of the variance

---
