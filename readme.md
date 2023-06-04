# Water Quality Parameter Prediction

This repository contains Jupyter Notebook files for predicting different water quality parameters using machine learning models. Each file focuses on predicting a specific parameter, namely:

- `Ammonia_Nitrogen.ipynb`: Predicts the Ammonia Nitrogen (mg/L) parameter.
- `BOD5.ipynb`: Predicts the 5-Day Biochemical Oxygen Demand (mg/L) parameter.
- `Nitrate_Nitrogen.ipynb`: Predicts the Nitrate Nitrogen (mg/L) parameter.
- `Total_Phosphorous.ipynb`: Predicts the Total Phosphorous (mg/L) parameter.

## Dependencies

The Jupyter Notebook files require the following dependencies:

- Python 3.x
- pandas
- scikit-learn
- numpy
- matplotlib

You can install the dependencies using the following command:

```shell
pip install pandas scikit-learn numpy matplotlib
```

## Usage

1. Clone the repository or download the Jupyter Notebook files.
2. Open the desired Jupyter Notebook file in Jupyter Notebook or JupyterLab.
3. Run the cells to train the model and evaluate the predictions.
4. The results will be displayed in batches of 100 data points.

## Dataset

The Jupyter Notebook files use a dataset specific to each parameter for training and testing the models. The dataset is not included in this repository. Please ensure that you have the appropriate dataset file for each parameter before running the Jupyter Notebook files.

## Results

The Jupyter Notebook files provide predictions for the respective water quality parameters. The results are shown in batches of 100 data points, allowing for a visual comparison between the actual and predicted values.

