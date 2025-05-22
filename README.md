# Car Sales Prediction Project

**Objective**  
Build and evaluate machine learning models that predict which used cars will sell the fastest, based on historical listings and vehicle attributes.

---

## Repository Contents

- `Car Sales Prediction Models.ipynb`  
  A Jupyter notebook that walks through the full analysis pipeline: loading data, exploratory analysis, cleaning & feature engineering, visualization, model training & evaluation, and a final “Attractiveness Score” prediction.

---

## Project Structure

1. **Data Loading**  
   - Read the CarStore3000 CSV into a Pandas DataFrame.  
   - Inspect column types and basic summary statistics.

2. **Exploratory Data Analysis**  
   - Examine distributions, missing values, and outliers.  
   - Visualize relationships (e.g., price vs. mileage, age vs. days-on-market).

3. **Data Cleaning & Wrangling**  
   - Impute or drop missing entries.  
   - Convert dates and categorical fields into usable formats.  
   - Create derived features (e.g., age of vehicle at listing).

4. **Data Visualization**  
   - Histograms, boxplots, scatter plots to surface key trends.  
   - Correlation heatmap to identify predictive features.

5. **Analysis Summary**  
   - **Key Findings:** Which factors (price, age, mileage, brand) most influence time-to-sale.  
   - **Next Steps:** Potential additional features, more advanced models, or data sources.

6. **Machine Learning Models**  
   - Split data into training and test sets using `train_test_split`.  
   - Train **Linear Regression** and **Random Forest Regressor** models.  
   - Evaluate performance with **Mean Absolute Error (MAE)** and **R² score**.

7. **Model Evaluation Results**  
   - Compare metrics across models.  
   - Discuss bias–variance tradeoffs and feature importance.

8. **Attractiveness Score Prediction**  
   - Derive a composite “Attractiveness Score” target.  
   - Retrain best-performing model to predict this score.

---

## Dependencies

- Python 3.8+  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

You can install all requirements with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
