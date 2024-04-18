
# Le Wagon Final Project

## Project Overview
This project was completed as part of the final assignment for the Le Wagon bootcamp. We utilized the Prophet machine learning model to predict the number of customers. The following outlines the workflow and methodologies employed in the project.


### Workflow Summary:

1) Authentication: 
Integrated Google Colab for running Python notebooks, ensuring a seamless cloud-based environment for data manipulation and model training.

2) Data Loading:
(Pre-COVID Data) Loaded historical data excluding the COVID period from Google BigQuery to analyze trends unaffected by the pandemic.
COVID-Inclusive Data: Loaded more recent data including the COVID period to understand the impact of the pandemic on customer trends.

3) Data Visualization:
Used Plotly to create interactive charts for both pre-COVID and COVID-inclusive datasets, providing a clear visual understanding of the data trends.

4) Data Preparation:
Splitting Data: Divided the pre-COVID data into training and testing sets.
Error Metrics Calculation: Computed MAPE and RMSE to evaluate the accuracy of the model on the test data.

5) Feature Engineering: 
Transformed date columns to datetime format in the COVID-inclusive dataset and created additional regression columns to capture COVID-related changes.

6) Model Configuration:
Set up the Prophet model with specific parameters.
Regression with COVID: Treated COVID as a regressor to account for its impact.
Seasonality Mode: Used a multiplicative approach to handle seasonal variations.
Growth Mode: Applied a logistic growth model to forecast the change in customer numbers.

7) Model Training and Prediction:
Training and Testing: Conducted over a 90-day period to fine-tune the model parameters and validate predictions.
Long-Term Forecast: Generated a 365-day forecast to predict future customer numbers.

8) Forecast Visualization: 
Utilized matplotlib's fig.gca() function to plot the prediction results, providing a clear and detailed visual representation of the forecasted customer trends.

### Conclusion
This project not only demonstrates the application of the Prophet model in forecasting but also showcases the ability to integrate machine learning techniques to solve real-world business challenges, highlighting the potential impacts of global events like the COVID pandemic on customer behavior.

For more details on the project setup, code, and results, please refer to the subsequent sections of this repository.

