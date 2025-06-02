# 📦 EGIER Bag Production Forecasting — Scientific Computing Project

This is a personal project for the **AOL Scientific Computing** course where I act as a **Data Scientist** at EGIER, an outdoor equipment manufacturer. The task? Analyze production trends, forecast capacity issues, and recommend when to build a new warehouse — all using Python-based scientific computing techniques.

## 🧠 Project Summary

EGIER has shared monthly production data for their warehouse from **January 2018 to December 2023 (144 months)**. The goal is to:

1. Find a precise **non-linear trend model** for production data.
2. **Convert the model to a numerical form** using Taylor series.
3. Predict **when production will exceed warehouse capacity** using root-finding (bisection method).
4. Share Python code to support all analysis.

## 🛠️ Tools & Techniques Used

- **Cubic Regression** for accurate trend modeling
- **Taylor Series Approximation** for numerical transformation
- **Bisection Method** for root-finding (capacity breach prediction)
- **Python + Google Colab** for implementation & plotting

## 📈 Key Findings

- **Model Chosen**: Cubic regression was selected over linear/quadratic due to higher flexibility and accuracy.
- **Equation**:  
  `y = 0.004x³ - 0.134x² + 47.224x + 1748.507`
- **Taylor Approximation** (at x=1):  
  `y(x) = 1795.601 + 46.968(x - 1) - 0.122(x - 1)² + 0.004(x - 1)³`
- **Prediction**: EGIER must start constructing a new warehouse by **Month 157** (out of 300) to accommodate future demand.

## 📊 Visualization Preview

- The model and Taylor series curves nearly overlap — confirming accuracy.
- Vertical markers show current capacity breach and construction deadlines.
- Capacity threshold marked by a horizontal line at 25,000 bags/month.

## 📂 Resources

- 📄 **Full Report PDF**: `AOL Scientific Computing - Kelvin Jonathan Yusach - 2702209533.pdf`
- 📊 **Raw Data Sheet**: [Google Sheets](https://docs.google.com/spreadsheets/d/1iSg4bEQfkfi2o58HmcMDII0i6InqnZrT/edit?usp=sharing)
- 💻 **Colab Notebooks**:
  - [Problem 1 - Trend Model](https://colab.research.google.com/drive/1QVicCPQPLcNih3Ao6cOLNrofBQrA9RHk?usp=sharing)
  - [Problem 2 - Taylor Approximation](https://colab.research.google.com/drive/1oeN6oxjXe2pC9trCFiu_LNGA8BvUl-bQ?usp=sharing)
  - [Problem 3 - Bisection Method](https://colab.research.google.com/drive/1BFnhCKiY1vOphMVSfjxKQEckwH4Gd69M?usp=sharing)

