# Temperature Converter: Linear Regression Model

## Project Overview
This project implements a machine learning model using Linear Regression to convert temperatures from Celsius to Fahrenheit. The model demonstrates a practical application of linear regression for a simple temperature conversion task.

## Dependencies
- pandas
- seaborn 
- scikit-learn
- numpy

## Dataset
The project uses a dataset stored in 'celsius.csv' containing temperature values in both Celsius and Fahrenheit scales.

## Model Description
The project utilizes a simple Linear Regression model from scikit-learn to learn the relationship between Celsius and Fahrenheit temperatures.

### Data Processing Steps
1. Load the data using pandas
2. Visualize the relationship using seaborn's scatterplot 
3. Process input data (X) and target data (y) by reshaping them for model compatibility
4. Train the Linear Regression model

### Model Training
The model is trained using the sklearn.linear_model.LinearRegression class and the processed temperature data.

## Usage
1. Ensure all dependencies are installed
2. Place the 'celsius.csv' file in the project directory
3. Run the notebook cells sequentially
4. Use the trained model to predict Fahrenheit temperatures from Celsius inputs

## Model Evaluation
The model's performance can be evaluated using the built-in score method, which calculates the R² score of the predictions.

## Project Structure
- `notebook.ipynb`: Main Jupyter notebook containing the model implementation
- `celsius.csv`: Dataset with temperature values (required for running the model)

## Author's Notes
This project serves as a basic introduction to Linear Regression, demonstrating how machine learning can be applied to solve simple real-world problems. The linear relationship between Celsius and Fahrenheit makes this an ideal case for Linear Regression.