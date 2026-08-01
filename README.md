# Predict Product Sales Performance
## Machine Learning Models to Forecast Retail Store Product Sales

**Author**: Dounia Nassar

### Business problem:

The objective is to help retail businesses forecast product sales accurately at various store outlets. By predicting sales performance, businesses can optimize inventory management, staffing, and marketing strategies based on data-driven insights.

### Data:

Dataset containing product sales records from multiple retail outlets with features including:
- Item characteristics (weight, type, visibility, price)
- Outlet information (type, location, establishment year, size)
- Target variable: Item sales across outlets
- Approximately 8,523 observations

## Methods

- **Data Exploration**: Analyzed sales distribution, feature correlations, and item visibility patterns across product types
- **Feature Engineering**: Processed categorical variables, handled missing values, and created meaningful feature representations
- **Model Development**: Trained multiple regression algorithms including Linear Regression, Decision Trees, and ensemble methods
- **Model Evaluation**: Compared models using performance metrics to identify the best predictor

## Results

### Item Outlet Sales Distribution
![Item Outlet Sales](https://github.com/user-attachments/assets/42409fee-0394-4acc-a97e-e9c627b251d5)

> Univariate analysis showing the distribution of sales across outlets, revealing patterns and potential outliers in the data.

### Feature Correlation Heatmap
![Correlation Heatmap](https://github.com/user-attachments/assets/9cfc98ea-1c2c-4c11-b822-534396b64cdf)

> Heatmap displaying correlation between features and sales, helping identify the most influential variables in predicting product sales.

### Item Visibility by Product Type
![Item Visibility by Type](https://github.com/user-attachments/assets/6c496503-621d-45bb-b8ec-e89d16a276e2)

> Multivariate analysis showing how item visibility varies across different product categories and its relationship with sales.

### Linear Regression Coefficients Plot
![Linear Regression Coefficients Plot](https://github.com/user-attachments/assets/e1905892-3a5c-4ab2-8385-c34198745db5)

> This plot shows the linear relationship between each feature and Item_Outlet_Sales. Item_MRP has a strong positive influence, meaning higher prices generally lead to higher sales. Outlet_Type_S has a strong negative relationship, indicating smaller outlets tend to have lower sales.

### Feature Importances
![Feature Importances](https://github.com/user-attachments/assets/e1905892-3a5c-4ab2-8385-c34198745db5)

> Feature importance plot from the ensemble model, displaying the relative contribution of each feature in predicting product sales. This helps identify which variables have the greatest influence on sales predictions.

## Model

The best performing model leverages ensemble techniques to capture non-linear relationships in sales data.

**Key Performance Metrics**:
- R² Score: [0.589]
- Mean Absolute Error (MAE): [739.759]
- Root Mean Squared Error (RMSE): [1,064.460]

This model successfully predicts product sales, enabling retailers to make data-driven decisions on inventory allocation and sales strategies.

## Recommendations:

- Focus inventory management on high-visibility items with strong price-to-sales correlations
- Tailor promotional strategies by product type and outlet location based on model insights
- Use sales predictions to optimize staffing levels during peak demand periods
- Monitor model performance regularly and retrain with new data quarterly

## Limitations & Next Steps

**Limitations**:
- Model performance may vary for new store locations with limited historical data
- External factors (seasonal trends, economic conditions) not captured in current dataset

**Next Steps**:
- Incorporate temporal features and seasonal indicators
- Integrate external economic and weather data
- Develop store-specific models for improved localized predictions
- Implement automated retraining pipeline for production deployment

  ---

## 👩‍💻 Author

**Dounia Nassar**
- 📧 dounia.nassar@outlook.com

