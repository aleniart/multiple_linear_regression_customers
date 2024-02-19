# Multiple Linear Regression based on eCommerce Customers Data

## Project Overview
This project aims to perform a Multiple Linear Regression (MLR) analysis based on eCommerce customer data. By leveraging statistical techniques and machine learning methodologies, the objective is to uncover the underlying relationships between various customer attributes and their annual expenditure on the eCommerce platform. Through this analysis, we endeavor to develop a predictive model that can effectively estimate the yearly amount spent by customers, utilizing features such as average session length, time spent on the app and website, and the length of membership.

## Dataset
The dataset used in this project was obtained from Kaggle.

## Building the Model
The process of building the MLR model involved the following steps:

- Splitting the data into training and testing sets.
- Initially, all significant variables were considered to build the model. Then, if any variable proved to be statistically insignificant, subsequent steps aimed to refine the model.
- Model evaluation was conducted using various statistical measures, including R-squared, adjusted R-squared, residual standard deviation and significance tests for coefficients.
- The final model was validated through tests for normality of residuals, heteroskedasticity and autocorrelation.

## Instructions

To utilize this project, follow these steps:

1. Ensure you have the necessary Python libraries installed. You can install them via pip or conda.
2. Clone this repository to your local machine.
3. Run the Jupyter Notebook or Python script to execute the analysis.
4. Customize the analysis or extend it to suit your specific requirements.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- plotly
- scikit-learn
- statsmodels

## Main files

- [`ecommerce_customers`](ecommerce_customers): Master dataset containing information about eCommerce customers.
- [`customer_model.ipynb`](customer_model.ipynb): Jupyter notebook with detailed steps of the analysis.

## Contributing
If you find issues or have suggestions for improvements, feel free to let me know.

## License
This project is licensed under the MIT License - see the [`LICENSE`](LICENSE) file for details.
