<!-- readme-refresh 2026-11 -->
<div align="center">

# 🛒 Product Recommendation System

**Content-based recommender for Amazon products**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" /> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" /> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />

</div>

## ✨ Highlights

- Product text turned into TF-IDF vectors
- Products ranked by cosine similarity
- EDA of prices, discounts, ratings and categories

<!-- body -->
Content-based recommender on the public Kaggle Amazon sales dataset (`amazon.csv`): product text is turned into
TF-IDF vectors and products are ranked by cosine similarity, so `get_recommendations("<product name>")` returns the
most similar products. The notebook also explores prices, discounts, ratings and categories.

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook main.ipynb
```

---

<div align="center"><sub>Built by <a href="https://github.com/Mokshitsharma">Mokshit Sharma</a> · <a href="https://mokshitsharma27.vercel.app/">Portfolio</a> · <a href="https://www.linkedin.com/in/mokshit-sharma-75b5ab305">LinkedIn</a></sub></div>
