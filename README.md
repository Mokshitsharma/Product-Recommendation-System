# Product Recommendation System

Content-based recommender on the public Kaggle Amazon sales dataset (`amazon.csv`): product text is turned into
TF-IDF vectors and products are ranked by cosine similarity, so `get_recommendations("<product name>")` returns the
most similar products. The notebook also explores prices, discounts, ratings and categories.

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook main.ipynb
```
