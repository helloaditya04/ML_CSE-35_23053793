# What is Encoding Categorical Data?

Encoding Categorical Data involves techniques like Ordinal Encoding and Label Encoding, which assign numeric values to categorical variables, facilitating model interpretation.



## Why Does Ordinal Encoding Matter?

The importance of ordinal encoding extends beyond just converting text to numbers. It has a **direct and significant impact** on the quality and accuracy of machine learning models.

When the wrong encoding technique is applied to ordinal data, the model receives incorrect information about the relationships between categories. For instance, if we use One Hot Encoding on education level data, we create four separate binary columns where all education levels appear equal. The model loses the crucial information that PhD is more advanced than a Bachelor's degree. This leads to poor model performance, incorrect predictions, and unreliable insights.

On the other hand, when ordinal encoding is correctly applied, the model can learn from the natural hierarchy in the data. A salary prediction model, for example, can correctly learn that higher education levels and higher experience levels correspond to higher salaries — a relationship that is only possible to capture when the data is properly encoded with ordinal encoding.

Furthermore, ordinal encoding matters for **data integrity and interpretability**. When we correctly encode ordered categories, the encoded values retain their real-world meaning. A data scientist looking at the encoded dataset can still understand what each value represents, making the analysis more transparent and interpretable.

---
