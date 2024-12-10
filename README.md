# Movie Search and Evaluation Metrics

## Overview
This project implements a movie search engine using an optimized search function. The search engine ranks movies based on user queries, and various evaluation metrics are computed to assess the performance of the search results. The primary metrics used for evaluation are Precision, Recall, nDCG (Normalized Discounted Cumulative Gain), and MRR (Mean Reciprocal Rank). The evaluation focuses on the top-k results, specifically Top-1 in this case.

## Features
- **Search Engine**: An optimized search function that returns top-k movie titles based on a user query.
- **Evaluation Metrics**:
  - **Precision@k**: Measures the proportion of relevant results in the top-k results.
  - **Recall@k**: Measures the proportion of relevant results retrieved out of all relevant results.
  - **nDCG@k**: Measures the relevance of the ranked results while accounting for position.
  - **MRR**: Calculates the average rank of the first relevant result in the search results.
  

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- Pandas 
- re
- SentenceTransformer
- faiss-cpu
- optuna
- matplotlib
- sklearn.metrics
- seaborn

## Dataset link
https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows

## detailed instructions and explanation in the below link
https://www.canva.com/design/DAGY3dEOjgA/plPBXrUshEaxHgv9CSt8JA/view?utm_content=DAGY3dEOjgA&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hfef7f189fc


