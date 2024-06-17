# Forecasting using SARIMAX model
### Introduction
---
This project centers around forecasting airline passenger numbers using the Seasonal Autoregressive Integrated Moving Average with eXogenous variables (SARIMAX) model. 
A core contribution of this work is the development of a custom function, `sarimax_optimizer_mae`, designed to automate the selection of the SARIMAX model's optimal parameters by minimizing the Mean Absolute Error (MAE) on a provided test dataset. The function iterates over a predefined range of parameters for both the non-seasonal and seasonal components of the model, fitting numerous SARIMAX models and evaluating their performance against the test set choosing the best SARIMAX model.
Upon determining the optimal parameter set, the selected SARIMAX model was applied to the entire dataset to forecast airline passenger numbers for the year following the dataset's last recorded observation. The model's forecasts were then visually compared against actual historical data to assess its predictive accuracy.

### Dataset
---
The dataset captures the monthly total airline passenger counts starting from 1949.
There are 144 monthly observations in the dataset.

### Steps involved
---
1. Data Collection
2. Data Preprocessing
3. Visual Analysis
4. Parameter Selection
5. Model Fitting
6. Model Diagnostics
7. Forecasting Future Values
8. Visualization and Reporting

These steps encompass the end-to-end process of using the SARIMAX model for forecasting airline passenger numbers, from initial data handling to making actionable forecasts.
Key findings from this project demonstrate the SARIMAX model's efficacy in capturing both the trend and seasonal components inherent in airline passenger data, thus providing valuable insights for planning and decision-making in the airline industry.

Tools and technologies used
---
- Python 3.8.10
- Jupyter Notebook

