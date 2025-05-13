# ColumnTransformer in Scikit-learn

This notebook showcases how to use `ColumnTransformer` to preprocess different types of features (categorical and numerical) in a machine learning dataset.

---

## 🧠 What is ColumnTransformer?

`ColumnTransformer` allows you to apply different transformations to different columns in a dataset:
- Encode categorical variables
- Scale numeric features
- Pass through or drop unused features

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `sklearn.preprocessing` for `StandardScaler`, `OneHotEncoder`
- `sklearn.compose.ColumnTransformer`

---

## 🚀 Steps Demonstrated

1. Load a dataset
2. Identify numerical and categorical columns
3. Apply transformations using `ColumnTransformer`
4. Integrate into a full pipeline (optional)
5. Transform and preview the results

---

## 🔧 Installation

```bash
pip install pandas numpy scikit-learn
```

---

## 📌 Why Use It?

- Simplifies preprocessing
- Keeps transformations organized
- Makes pipelines cleaner and reusable

---

## ✅ Output

You’ll see side-by-side transformations applied appropriately per column type and understand how to scale this for real projects.

---

**Author**: Auto-enhanced by ChatGPT for GitHub use.
