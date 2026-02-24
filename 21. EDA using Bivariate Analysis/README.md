# Bivariate Analysis

Bivariate analysis is the simultaneous analysis of two variables to understand the relationship between them — whether they are related, how strongly, and in what direction.

The word "bi" means two, so bivariate simply means we're looking at two variables at a time, as opposed to univariate (one variable) or multivariate (many variables).

---

## Core Questions It Answers

- Is there a relationship between Variable A and Variable B?
- How strong is that relationship?
- What is the direction of the relationship (positive or negative)?

---

## Simple Example: Study Hours vs. Exam Score

Suppose you collect data from 5 students:

| Student | Study Hours (X) | Exam Score (Y) |
|----------|-----------------|----------------|
| A        | 2               | 50             |
| B        | 4               | 65             |
| C        | 6               | 75             |
| D        | 8               | 85             |
| E        | 10              | 95             |

Here, X = Study Hours and Y = Exam Score are our two variables. Bivariate analysis would reveal that as study hours increase, exam scores also increase — a positive relationship.

---

## Types of Bivariate Analysis

The method you use depends on the type of variables involved:

### 1. Both variables are Numerical → Correlation & Scatter Plot

Using the example above, you'd calculate the Pearson correlation coefficient (r).  
An r close to +1 means a strong positive relationship.  
In our case, r would be very close to 1, confirming that more study hours = higher scores.

### 2. One Numerical, One Categorical → T-test or ANOVA

Example: Does gender affect salary?  
Here gender is categorical (Male/Female) and salary is numerical.  
You'd compare the average salary across groups.

### 3. Both variables are Categorical → Chi-Square Test

Example: Is there a relationship between smoking (Yes/No) and lung disease (Yes/No)?  
You'd build a contingency table and run a chi-square test to see if the two are independent or associated.

---

## Key Techniques at a Glance

| Situation                     | Technique                                      |
|--------------------------------|-----------------------------------------------|
| Numerical vs. Numerical        | Scatter plot, Correlation (Pearson/Spearman) |
| Categorical vs. Numerical      | Box plot, T-test, ANOVA                      |
| Categorical vs. Categorical    | Contingency table, Chi-Square test           |

---

## Why It Matters ?

Bivariate analysis is a foundational step in data analysis and machine learning. Before building models, analysts use it to identify which variables are related to the outcome they care about (e.g., which factors influence sales, disease risk, or customer churn). It helps separate meaningful signals from noise.
