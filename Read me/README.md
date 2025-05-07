# 🍽️ Restaurant Rating Analysis

## 📊 Overview

This project analyzes restaurant data to uncover customer preferences and understand the impact of factors like cuisine, cost, and services on customer ratings. It includes exploratory data analysis, feature engineering, and machine learning modelling to predict restaurant ratings. 

## 📁 Dataset

- **Source:** [Restaurant Dataset CSV](https://raw.githubusercontent.com/Oyeniran20/axia_class_cohort_7/refs/heads/main/Dataset%20.csv)
- **Format:** CSV
- **Records:** 9,551 restaurants
- **Key Fields:** Cuisines, City, Average Cost, Rating, Votes, Services
- **Target Variable:** Aggregate Rating

## ⚙️ Installation & Setup

1. Install [Anaconda](https://www.anaconda.com/) and launch **Jupyter Notebook**.
2. Clone or download this repository and navigate to the project directory.
3. Open the notebook file in Jupyter: `Restaurant_Rating_Analysis.ipynb`
4. Run all cells to reproduce the analysis.

> **Note:** All required libraries are standard in Anaconda: `pandas`, `numpy`, `matplotlib`, and `seaborn`.

## 🚀 Usage

- Simply open the notebook in Jupyter and run all cells sequentially.
- The dataset is automatically loaded from the provided GitHub link.
- No manual parameter configuration or local file uploads are required.

## 📈 Results & Findings

Here are a few highlights from the analysis:

- **Votes and Rating Correlation:** More popular cuisines (with higher vote counts) tend to have higher ratings.
- **Cuisine Insights:** Italian cuisine ranked highest among popular categories (votes ≥ 50).
- **Cost & Ratings:** Higher-priced restaurants typically receive better ratings.
- **Service Impact:** Restaurants offering delivery or table bookings had improved customer ratings.
- **Model Performance:** A Random Forest Regressor achieved ~82% prediction accuracy, outperforming linear and XGBoost models.

![](C:\Users\DELL\AppData\Roaming\marktext\images\2025-05-07-13-02-38-image.png)  

> *Image from presentation illustrating rating trends by cuisine*

## 🧠 Methodology

- **Data Cleaning & Feature Engineering**
  
  - Imputation of missing values
  - Feature transformations (e.g., log transformation on cost)
  - Encoding of categorical variables

- **Exploratory Data Analysis**
  
  - Distribution plots, correlation heatmaps, and boxplots
  - Cost, cuisine, and service-based segmentation

- **Machine Learning Models**
  
  - Linear Regression
  - Random Forest Regressor (best performance)
  - XGBoost Regressor

- **Evaluation Metrics**
  
  - R² Score
  - Root Mean Squared Error (RMSE)

## 🧪 Limitations

- Imbalanced rating distribution (many 0.0 ratings are treated as NaN)
- Cuisine data heavily biased toward Indian cuisine
- Weak geographic correlation (location had minimal impact on ratings)

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

**Gabriel Amao**  
📧 [Email](mailto:ojoayoamao9418@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ojoayo)

---

*For a deeper visual overview, see the accompanying project presentation.*
