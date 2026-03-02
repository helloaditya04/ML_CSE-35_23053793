# 📌 Normalization in Machine Learning

## 🔹 What is Normalization?

**Normalization** is a data preprocessing technique used in machine learning to scale numerical features to a common range.

It helps:
- Prevent certain features from dominating others
- Improve model performance
- Speed up convergence in gradient-based algorithms
- Ensure fair contribution of all features

Normalization changes the values of numeric columns without distorting differences in the ranges or losing information.

---

## 🔹 Why Do We Need Normalization?

Different features may have different ranges.

Example:

| Feature | Range |
|----------|--------|
| Age | 18 – 60 |
| Salary | 10,000 – 1,000,000 |

Without normalization:
- Larger value features (like Salary) may dominate smaller ones (like Age).

---

## 🔹 Types of Normalization / Scaling Techniques

### ✅ 1. Min-Max Normalization (Min-Max Scaling)

Scales values to a fixed range (usually **[0,1]**).

**Formula:**

```
X' = (X - Xmin) / (Xmax - Xmin)
```

✔ Keeps original distribution shape  
✔ Sensitive to outliers  

---

### ✅ 2. Mean Normalization

Centers data around zero.

**Formula:**

```
X' = (X - Mean) / (Xmax - Xmin)
```

✔ Useful when centering data  

---

### ✅ 3. MaxAbs Scaling

Scales data by dividing by maximum absolute value.

**Formula:**

```
X' = X / |Xmax|
```

✔ Preserves sparsity  
✔ Good for sparse datasets  

---

### ✅ 4. Robust Scaling

Uses Median and Interquartile Range (IQR).

**Formula:**

```
X' = (X - Median) / IQR
```

✔ Not affected by outliers  
✔ Good for skewed data  

---

## 🔹 Summary

Normalization is an essential preprocessing step in machine learning that:

- Improves model stability
- Ensures balanced feature contribution
- Helps many algorithms perform better
