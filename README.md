# Inventory Demand Forecasting

## Project Overview
This project aims to forecast inventory demand using machine learning to help businesses manage stock effectively and reduce costs. By utilizing historical sales data and predictive models, the goal is to optimize inventory levels, minimizing overstock or stockout situations.

## Dataset
The dataset includes:
- **Product_Code**: Product identifier.
- **Warehouse**: Location of the product.
- **Product_Category**: Product category.
- **Date/Week**: Date or week of recorded demand.
- **Sales/Demand**: Sales or demand value.

## Preprocessing Steps
- **Missing Value Treatment**: Impute or remove missing values.
- **Outlier Handling**: Detect and manage outliers.
- **Categorical Encoding**: Use Label or One-Hot Encoding for categorical features.
- **Feature Engineering**: Extract week/month from Date for seasonality patterns.

## Exploratory Data Analysis (EDA)
- **Demand Trends**: Visualize demand over time.
- **Demand per Product/Warehouse**: Identify top-demand products and locations.
- **Seasonality Patterns**: Detect cyclical demand variations.
- **Correlation**: Analyze relationships between features and demand.

## Machine Learning Models
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **XGBoost Regressor**

## Evaluation Metrics
Models evaluated using:
- **RMSE** (Root Mean Squared Error)
- **MAE** (Mean Absolute Error)
- **R² Score**

## Insights & Results
- Feature importance analysis.
- Comparison of model performance.
- Best model (likely XGBoost or Random Forest) selected for demand forecasting.

## Forecasting
The best model is used to predict future inventory demand. Forecasted data is saved in `forecasted_demand.csv` for planning/logistics.

## Fine-Tuning
Models are fine-tuned using techniques like GridSearchCV or RandomizedSearchCV to improve performance.

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/inventory-demand-forecasting.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook `inventory_forecasting.ipynb` to preprocess data, train models, and evaluate performance.
4. Use the trained model to forecast demand.

## License
MIT License

## Acknowledgements
- Dataset from Kaggle or similar
- Libraries: Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn

