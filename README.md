# Sales Prediction using Python

## Project Overview
This project focuses on predicting product sales based on advertising expenditure across TV, Radio, and Newspaper platforms using Python and Machine Learning.

It is developed as part of the CodeAlpha Data Science Internship (Task 4).

## Objectives
- Analyze advertising expenditure and sales data.
- Clean and preprocess the dataset.
- Perform Exploratory Data Analysis (EDA).
- Build a Multiple Linear Regression model.
- Predict sales using advertising expenditure.
- Evaluate model performance.
- Provide business and marketing recommendations.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Dataset
The project uses the Advertising.csv dataset provided through the CodeAlpha internship task.

Dataset features:
- TV
- Radio
- Newspaper
- Sales

The original dataset contains 200 records.

## Machine Learning Model
Multiple Linear Regression is used to predict sales based on TV, Radio, and Newspaper advertising expenditure.

## Model Evaluation
The model is evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R2)

## Visualizations
The images folder contains:
1. Correlation Heatmap
2. Sales Distribution
3. Advertising vs Sales
4. Actual vs Predicted Sales
5. Advertising Impact on Sales Prediction

## Project Structure
- CodeAlpha_SalesPrediction.ipynb - Main Python notebook.
- images/ - Project visualizations.
- requirements.txt - Required Python libraries.
- .gitignore - Files excluded from Git tracking.

## How to Run
1. Clone or download this repository.
2. Install dependencies using:
   pip install -r requirements.txt
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Upload the Advertising.csv dataset when prompted.
5. Run the notebook cells in order.

## Limitations
The supplied dataset does not contain dates or target-segment information. Therefore, this project uses regression-based sales prediction rather than time-series forecasting or segment-wise analysis.

## Internship
Developed as part of the CodeAlpha Data Science Internship.

## Author
Vaibhav Surase