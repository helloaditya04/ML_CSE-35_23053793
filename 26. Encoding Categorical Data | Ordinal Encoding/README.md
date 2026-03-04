# What is Ordinal Encoding ?

Ordinal Encoding is a data preprocessing technique used in machine learning to convert ordered categorical data into numerical values.

Machine learning models cannot understand text-based categories. They require numerical input.
Ordinal encoding solves this problem while preserving the natural order of categories.

Ordinal Encoding assigns integers to categories based on their rank or hierarchy.

It is specifically used for categorical data where the order of categories is meaningful.

```
Low     → 1
Medium  → 2
High    → 3
```

# Why is Ordinal Encoding Used?

Ordinal Encoding is used because:

- Machine learning algorithms require numerical input.
- It preserves the natural ranking between categories.
- It allows models to understand progression or hierarchy.
- It is memory efficient (uses only one column).
- Without preserving order, important information about hierarchy may be lost.

## Why Does It Matter?

Encoding directly impacts model performance.

If ordered data is encoded incorrectly:

- The model may learn false relationships.
- Predictions may become inaccurate.
- The logical structure of the data may be distorted.

When applied correctly:

- The model understands ranking.
- Patterns become more meaningful.
- Prediction accuracy improves.

Proper encoding ensures data integrity and better learning.

---

## When to Use Ordinal Encoding

Use Ordinal Encoding when:

- Categories have a clear and meaningful order.
- The ranking affects prediction.
- Hierarchy is important in the dataset.
