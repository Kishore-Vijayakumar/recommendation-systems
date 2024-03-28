# Smartphone Recommendation System

## Overview
This project focuses on building a recommendation system for smartphones using popularity-based and collaborative filtering techniques. The aim is to recommend mobile phones that are either the most popular or personalized based on user behavior.

---

## Features
- **Domain**: Smartphone, Electronics
- **Objective**: Develop a recommendation system to suggest mobile phones to users.
- **Techniques**:
  - Popularity-based recommendations
  - Collaborative filtering using SVD and kNNWithMeans
  - Data preprocessing, analysis, and model evaluation

---

## Tools and Technologies
- **Languages**: Python
- **Libraries**: pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Surprise

---

## Key Steps
1. **Data Preprocessing**:
   - Merged and cleaned datasets.
   - Imputed missing values and removed duplicates.
   - Selected relevant features like `Author`, `Product`, and `Score`.
2. **Exploratory Analysis**:
   - Identified top-rated features and active users.
   - Filtered data for products with >50 ratings and users with >50 reviews.
3. **Model Building**:
   - Built a popularity-based model to recommend top 5 mobile phones.
   - Developed collaborative filtering models using SVD and kNNWithMeans.
4. **Model Evaluation**:
   - Evaluated collaborative filtering models using RMSE.
   - Recommended top 5 products for test users.
5. **Recommendations**:
   - Compared use cases for popularity-based and collaborative filtering systems.
   - Proposed methods to improve recommendations.

---

## Notes
- Due to licensing restrictions, the dataset used for this project is not included in the repository.

---
