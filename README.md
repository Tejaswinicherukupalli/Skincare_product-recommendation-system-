# Skincare Product Recommendation System

This repository contains a machine learning-based recommendation system for skincare products. It leverages user behavior data to suggest relevant products, brands, and price ranges, improving the retail experience with personalized recommendations.

---

## Project Overview

The project uses a multi-output neural network model to predict:
- Product preferences.
- Brand choices.
- Skin type compatibility.
- Price expectations.

### Features:
- **Exploratory Data Analysis (EDA)** to understand customer trends.
- **Preprocessing** for handling missing data and encoding features.
- **Model Training** using embedding layers and dense neural networks.
- **Evaluation Metrics**: Precision, Recall, F1-score, and MAE (Mean Absolute Error).

---

## Dataset

The dataset includes fields such as:
- `User ID`
- `Product`
- `Brand`
- `Skin Type`
- `Price`
- `Sold By`

### Preprocessing:
1. Imputation of missing values (mode for categorical, median for numerical data).
2. Encoding of categorical fields.
3. Scaling of numerical features using MinMaxScaler.

---

## How It Works

1. **Data Processing**:
   - Missing values are filled.
   - Categorical features are encoded for machine learning.
   - Data is split into training and testing sets.

2. **Model Training**:
   - Embedding layers are used for product, brand, and skin type.
   - Dense layers combine these embeddings to predict outputs.

3. **Evaluation**:
   - Metrics include Precision, Recall, F1-score, and Mean Absolute Error (MAE).
   - Training and validation loss/accuracy trends are visualized.

---

## Model Performance

| Metric               | Score |
|----------------------|-------|
| Precision (Product)  | 0.85  |
| Recall (Product)     | 0.83  |
| F1-Score (Product)   | 0.84  |
| Mean Absolute Error (Price) | 5.20 |

---

## Getting Started

### Prerequisites
- Python 3.8+
- Libraries:
  - Pandas
  - NumPy
  - Scikit-learn
  - TensorFlow
  - Seaborn
  - Matplotlib

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/skincare-recommendation.git
   cd skincare-recommendation

