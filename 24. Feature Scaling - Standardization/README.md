## 1. What is Feature Scaling?

Feature Scaling is a preprocessing technique used in Machine Learning to bring all features (variables) to a similar scale or range.

### Why is it important?
- Prevents features with large values from dominating smaller ones
- Improves model performance
- Helps algorithms converge faster

---

## 2. What is Standardization?

Standardization (also called **Z-Score Normalization**) is a type of feature scaling.

It transforms data so that:

- Mean (μ) = 0  
- Standard Deviation (σ) = 1  

---

## Formula

```
Z = (X - μ) / σ
```

### Where:
- **X** = Original value  
- **μ** = Mean of the feature  
- **σ** = Standard deviation of the feature  
- **Z** = Standardized value  

---

## Summary

| Topic | Description |
|-------|------------|
| Feature Scaling | Brings all features to a similar scale |
| Standardization | Makes mean = 0 and standard deviation = 1 |

---

Apply scaling after splitting the dataset into training and testing sets.  
Fit the scaler only on training data.
