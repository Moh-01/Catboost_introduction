![](/assets/images/ga_logo.png)
 prepared by: *Mohammed Al-hamad*
 
----
<br>

# Catboost introduction

![](/assets/images/orig.png)

Catboost can be used for solving problems, such as:
- Regression.
- Classification.
- Multi-class classification.

Modes differ by the objective function, that we are trying to minimize during gradient descent.
 - Catboost have pre-build metrics to measure the accuracy of the model.
 - In the official catboost website you can find the comparison of Catboost ([Benchmarks](https://catboost.ai/#benchmark)) with major benchmarks.

---
# Contents
- Introduction
  - Sparse data?<br><br>
- What is CatBoost?
  - Comparisons
  - Catboost sensitivity to Hyper Parameter
  - Section Conclusion<br><br>
- Advantages and disadvantages of CatBoost algorithm<br><br>
- Comparing CatBoost to other boosting algorithms
  - Installing CatBoost
  - Restriction & Requirements
  - Instaling<br><br>
- Using CatBoost
  - Titanic dataest
  - Catboost Model
  - Kaggle score
---

# Introduction

- Catboost is a fast, scalable, high performance Gradient Boosting on Decision Trees library, used for ranking, classification, regression and other machine learning tasks for `Python`, `R`, `Java`, and `C++`.

- Supports computation on CPU and GPU.

- There are several gradient boosting libraries available: 
  - XGBoost
  - H20
  - LightGBM
- The main difference between them is the tree structure, feature engineering, and working with sparse data.
