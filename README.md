# 🚗 AutoML Frameworks for Sustainable Fuel Efficiency Predictions

A comparative AutoML-based regression framework built to predict vehicle fuel efficiency (MPG) using the UCI Auto MPG dataset. This project evaluates and benchmarks multiple AutoML tools including **PyCaret**, **H2O.ai AutoML**, **TPOT**, and **Gradient Boosting Regressor**, offering insights into their performance, ease of use, and predictive accuracy.

---

## 📊 Objective

The goal of this project is to:
- Predict miles per gallon (MPG) for cars based on engine and vehicle characteristics.
- Leverage automated machine learning tools to reduce model selection and tuning overhead.
- Benchmark and compare different AutoML systems for sustainable vehicle performance modeling.

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository – Auto MPG Dataset](https://archive.ics.uci.edu/ml/datasets/auto+mpg)
- **Features**:
  - Cylinders
  - Displacement
  - Horsepower
  - Weight
  - Acceleration
  - Model Year
  - Origin (encoded as USA, Europe, Japan)
- **Target**: `MPG` – Miles per Gallon (fuel efficiency)

---

## 🛠️ Tools & Frameworks Used

| Framework      | Purpose                                |
|----------------|----------------------------------------|
| PyCaret        | Quick AutoML pipeline & tuning         |
| H2O.ai AutoML  | Scalable model search & leaderboard    |
| TPOT           | Genetic programming-based pipeline     |
| Sklearn + GBR  | Baseline Gradient Boosting Regressor   |
| Pandas/Seaborn | EDA and preprocessing                  |

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/your-username/automl-fuel-efficiency.git
cd automl-fuel-efficiency

