# Store Sales - Time Series Forecasting

This is a student Term Project in `Data Mining` by Prof. Anthony J.T. Lee, National Taiwan University.

## Quick Links

- [Data Mining Term Project](https://github.com/brianCHUCHU/Store-Sales---Time-Series-Forecasting): For detailed documentation in formal PDF format.
- [Slides](https://github.com/brianCHUCHU/Store-Sales---Time-Series-Forecasting/blob/main/Slides.pdf): For presentation slides in PDF format.

## Store Sales Time Series Forecasting

This repository contains the code and analysis for a term project focusing on forecasting store sales using time series data from Corporación Favorita, a large retailer in Ecuador. The project aims to predict the total sales volume of various product categories within each store over the next 16 days.

### Summary

The project employs various machine learning models to predict sales volume, helping to minimize product waste and ensure sufficient inventory levels, ultimately enhancing customer satisfaction. Key methodologies and findings include:

- **Data Analysis**: Explored correlations between store sales and factors such as oil prices, promotions, and store clusters.
- **Modeling Approaches**: Developed and compared the performance of various models, including Linear Regression, Ensemble Learning, and Time Series models.
- **Feature Engineering**: Implemented techniques such as min-max normalization, word embedding, and one-hot encoding to improve model accuracy.
- **Data Preprocessing**: Merged and cleaned datasets, handling missing values and extracting relevant features for analysis.

### Methodologies

#### Linear Regression Models

- **Multi-index Linear Model**: Treats each data point as an independent observation, offering simplicity and direct interpretation of coefficients.
- **Moving Average (MA)**: Smooths short-term fluctuations to highlight longer-term trends.
- **Exponential Smoothing**: Assigns exponentially decreasing weights to past observations for more responsive trend analysis.
- **ARIMA Models**: Combines autoregression, differencing, and moving average components to handle various time series patterns.

#### Ensemble Models

- **Random Forest**: Constructs multiple decision trees to improve accuracy and control overfitting.
- **XGBoost**: A powerful and efficient gradient boosting framework known for its scalability and performance.
- **LightGBM**: Optimized for speed and memory usage, suitable for large-scale data and high-dimensional features.
- **CatBoost**: Handles categorical features automatically, offering robust performance with fewer hyperparameters.

#### Multi-Index LSTM Model

- **Multi-Index Transformation**: Converts sales data into a multi-index format for better time-series analysis.
- **Sequence Creation**: Constructs sequences of data for LSTM model input.
- **Model Construction**: Comprises multiple LSTM and Dropout layers, with Adam optimizer and MSLE loss function.

### Future Research Suggestions

- **Data Limitations**: Addressing limitations such as insufficient information on parking dock vacancies and weather data coverage to enhance model accuracy.
- **Expanding Scope**: Considering data outside the initial dataset and analyzing network relationships between locations.
- **Automation Tools**: Developing automated tools combining proposed models and methods to increase operational efficiency further.

### Repository Structure

- **Code**: Contains Python scripts and Jupyter Notebooks for data analysis, modeling, and predictions.
- **Data**: Includes datasets used for analysis, such as store sales data and supplementary data sources.
- **Reports**: Contains project documentation, analysis reports, and presentation slides.

### Contributors

This project was conducted by students enrolled in the Data Mining course at National Taiwan University.

- Yu-Ting Huang
- Chieh-Hsiang Hsu
- Sen-Yun Ku
- Po-Yen Chu
- Pin-Cheng Chen
