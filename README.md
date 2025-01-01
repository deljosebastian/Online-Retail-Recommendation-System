# Online Retail Recommendation System

This project focuses on developing an **Online Retail Recommendation System** using Python. The system recommends products to users based on historical retail data.

## Dataset

The dataset used in this project contains the following columns:
- **Invoice Number**: Identifies a transaction.
- **Stock Code**: Product ID.
- **Description**: Description of the purchased product.
- **Quantity**: Number of items purchased.
- **Invoice Date**: Date of the transaction.
- **Unit Price**: Price of a single product unit.
- **Customer ID**: Identifies the customer.
- **Country**: Country where the transaction took place.

The dataset was sourced from Kaggle and includes historical data on online retail transactions.

---

## Features

1. **Data Preprocessing**:
   - Handle missing values.
   - Filter data for meaningful recommendations.

2. **Model Development**:
   - Transform product descriptions using  **CountVectorizer**.
   - Dimensionality reduction with **Truncated SVD** (optional).
   - Product similarity computation using **Nearest Neighbors**.

3. **Scalable Recommendations**:
   - Recommend products using cosine similarity.
   - Batch processing for large datasets.



## Acknowledgments

- **Kaggle** for providing the dataset.
- **scikit-learn** for machine learning utilities.

