
#🏡 Paris Housing Market Trends Analysis and Prediction

![Project Badge](https://img.shields.io/badge/Project-Paris%20Housing%20Market%20Analysis-blueviolet?style=flat-square)

This project analyzes the Paris housing market to uncover key drivers of property prices and builds a predictive model to estimate future price trends.  
By exploring housing features such as number of bedrooms, property grade, and living area, the study offers actionable insights for estate management and investment strategy.

---

## 🔍 Project Summary

We conducted a detailed exploratory analysis and predictive modeling using a Paris housing dataset (~20,000 properties).  
The primary objectives were:
- Investigate the relationship between **bedroom count** and **housing prices**.
- Study the impact of **floor count and total living area**.
- Build a reliable **price prediction model**.

Models evaluated:
- Linear Regression ✅ (Selected)
- Ridge Regression
- Lasso Regression
- Random Forest Regressor

---

## 📈 Model Performance Comparison

| Model              | MAE    | RMSE   | R²     |
|--------------------|--------|--------|--------|
| Linear Regression  | 0.2812 | 0.3492 | 0.5722 |
| Ridge (α=10.0)      | 0.2812 | 0.3492 | 0.5722 |
| Lasso (α=0.0001)    | 0.2812 | 0.3492 | 0.5722 |
| Random Forest       | 0.2931 | 0.3698 | 0.5202 |




