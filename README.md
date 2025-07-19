# Smart_irrigation


This project uses machine learning to automate irrigation decisions based on environmental parameters like temperature, humidity, and soil moisture. It is implemented in Python using a Jupyter Notebook.

## Project Structure

- `Irrigation_System.ipynb`: Main Jupyter Notebook file containing:
  - Data preprocessing
  - Exploratory data analysis (EDA)
  - Model training and evaluation
  - Predictions based on input features

## Features

- Read and process sensor data (CSV file format)
- Perform exploratory analysis with visualizations
- Train machine learning models (e.g., Decision Tree, Random Forest)
- Predict whether irrigation is required or not
- Evaluate model accuracy using metrics

## Input Data

The model expects a CSV dataset with the following sample features:

- Temperature
- Humidity
- Soil Moisture
- Irrigation Required (Target variable)

**Note:** Make sure the dataset path in the notebook is correctly set to your local file system.

## Technologies Used

- Python 3
- pandas
- matplotlib / seaborn
- scikit-learn
- Jupyter Notebook

## How to Run

1. Clone the repository or download the notebook.
2. Make sure you have Python and Jupyter installed.
3. Place your dataset (e.g., `irrigation_machine.csv`) in the appropriate path.
4. Run the notebook:
