# E-Commerce Recommendation System Using Collaborative Filtering

## Introduction
This project implements an E-Commerce Recommendation System that suggests relevant products to users based on their past interactions.
It uses Collaborative Filtering techniques to analyze user behavior and generate personalized recommendations.

## Objectives
- Build a recommendation engine for an e-commerce dataset
- Implement User-Based and Item-Based Collaborative Filtering
- Evaluate recommendations using Precision@K and Recall@K
- Generate Top-N product recommendations

## Problem Statement
Users face difficulty finding relevant products among thousands of options.
This system addresses the problem by recommending products based on similar users and similar items.

## Dataset
The dataset contains historical user–item interaction data in CSV format:
user_id, item_id, rating

## Preprocessing
- Removed users with very few interactions
- Removed items with very few interactions
- Cleaned data improves recommendation quality

## Methodology
1. Load and preprocess data
2. Convert data to Surprise format
3. Split data into training and testing sets
4. Train User-Based and Item-Based models
5. Evaluate using Precision@K and Recall@K
6. Generate recommendations

## Algorithms Used
- User-Based Collaborative Filtering (Cosine Similarity)
- Item-Based Collaborative Filtering (Cosine Similarity)

## Evaluation Metrics
- Precision@K
- Recall@K

These metrics are suitable for recommender systems.

## Results
The system outputs:
- Precision@5 and Recall@5 values
- Top-5 recommendations for sample users

## Tools & Technologies
- Python
- Pandas
- NumPy
- Surprise
- Google Colab

## How to Run (Google Colab)
1. Install dependencies:
   pip uninstall -y numpy scikit-surprise
   pip install numpy==1.26.4
   pip install scikit-surprise
2. Restart runtime
3. Upload files
4. Run all cells

## Limitations
- Cold-start problem
- Scalability issues for very large datasets

## Future Enhancements
- Matrix Factorization (SVD)
- Hybrid recommendation system
- Web app deployment

## Conclusion
This project demonstrates an effective collaborative filtering–based recommendation system that follows standard academic and industry practices.