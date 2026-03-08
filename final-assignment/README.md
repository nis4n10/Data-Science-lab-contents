### TEAM MEMBERS:
##### Nishan K.C.: ACE081BCT046
##### Joshan Dhakal: ACE081BCT034



# Laptop Price Prediction

A machine learning project that explores what actually drives laptop prices — and whether we can predict them from hardware specs alone.

---

## Overview

Ever wondered why two laptops with similar-looking specs can have a €1,000 price gap? This project tries to answer that. Using a dataset of 1,275 laptops, I built two models:

- **Linear Regression** — to predict the actual price of a laptop in Euros
- **Logistic Regression** — to classify whether a laptop is high-end or budget/mid-range (split at the median price)

---

## Project Structure

```
├── final_project-.ipynb   # Main notebook
├── laptop_price.csv                      # Dataset
└── README.md
```

---

## Objectives

- Identify which hardware specs have the strongest influence on laptop price
- Build a regression model to predict price as a continuous value
- Build a classification model to label laptops as high-end or budget/mid-range
- Evaluate and interpret both models

---

## Tech Stack

- Python 3
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## How to Run

1. Clone the repo and navigate to the project folder
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Laptop_Price_Assignment_Fixed.ipynb
   ```
4. Run all cells from top to bottom

---

## Key Finding

RAM and CPU frequency are by far the strongest predictors of laptop price — more so than brand. If you're shopping for a laptop, focus on what's inside rather than the logo on the lid.




