# USA_house_prices_model
Predict the price of a house. This project applies data preprocessing, feature engineering, and model building to develop a predictive model for house prices.

## Table of Contents
- Project Overview
- Dataset
- Project Workflow
- Model Performance
- Project Structure
- License

### Project Overview
This project aims to build a Regression model that predicts house prices based on various house features, such as sqft_living, conditions, city, etc. Techniques like exploratory data analysis (EDA), data preprocessing, and machine learning modeling was used to achieve a model.

### Dataset
The dataset used for this project includes:

 - Date
 - Price (Target variable)
 - Bedrooms
 - Bathrooms
 - Sqft Living
 - Sqft Lot
 - Floors
 - Waterfront
 - View
 - Condition
 - Sqft Above
 - Sqft Basement
 - Yr Built
 - Yr Renovated
 - Street
 - City
 - StateZip
 - Country

### Project Workflow
 - **Data Exploration**: Analyze the data, visualize distributions, and understand feature relationships.
 - **Data Preprocessing**: Handle missing values, outliers, and encode categorical variables.
 - **Feature Engineering**: Extract and select relevant features.
 - **Model Building**: Train various machine learning models and evaluate their performance.
 - **Evaluation**: Assess the model on test data and interpret results.

### Model Performance
The model achieved:


| Model | MAE | R-squared |
| --- | --- | --- |
| rfr |	130937.330306 |	0.455970 |
| --- | --- | --- |
| xgb |	131917.383047 |	0.445956 |
| --- | --- | --- |
| ridge |	139014.188848 |	0.480514 |
| --- | --- | --- |
| lasso |	139718.825651 |	0.467395 |
| --- | --- | --- |
| gbr |	140210.871723 |	0.428785 |
| --- | --- | --- |
| cat |	148126.392531 |	0.271991 |
| --- | --- | --- |
| lgbm |	153767.715331 |	0.242492 |
| --- | --- | --- |
| elnet |	160611.590026 |	0.435284 |
| --- | --- | --- |
| dtr |	169239.522193 |	-0.100817 |
| --- | --- | --- |
| svr |	220812.471993 |	-0.065730 |
| --- | --- | --- |
| mlp |	222662.264570 |	0.081266 |

License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
