# Predict Product Sales Performance
## Machine Learning Models to Forecast Retail Store Product Sales

**Author**: Dounia Awni

### Business problem:

The objective is to help retail businesses forecast product sales accurately at various store outlets. By predicting sales performance, businesses can optimize inventory management, staffing, and marketing strategies for different product categories and store locations.

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

## Model

The best performing model leverages ensemble techniques to capture non-linear relationships in sales data.

**Key Performance Metrics**:
- R² Score: [Add your score]
- Mean Absolute Error (MAE): [Add your MAE]
- Root Mean Squared Error (RMSE): [Add your RMSE]

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

### For further information

For any additional questions, please contact **Dounia Awni**
- GitHub: [@Dounia-Awni](https://github.com/Dounia-Awni)
- Email: [Add your email]
