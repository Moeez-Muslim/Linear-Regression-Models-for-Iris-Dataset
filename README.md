# Linear Regression Models for Iris Dataset

This repository contains Python code for building and comparing linear regression models using the Iris dataset. Two models are implemented to predict the petal width based on different independent variables (sepal length and petal length). The models are built using the probabilistic programming library PyMC.

## Overview

- **Data Source**: The Iris dataset is imported from the "iris.csv" file using the Pandas library.
- **Correlation Analysis**: Pearson's correlation coefficients are calculated for pairs of features to decide the independent variable for each model.
- **Model 1**: Linear regression model with petal length as the independent variable.
- **Model 2**: Linear regression model with sepal length as the independent variable.
- **R-Squared Comparison**: R-squared values are calculated to evaluate the goodness of fit for each model.

## Dependencies

Make sure you have the following dependencies installed:

- Python (>=3.6)
- NumPy
- Pandas
- PyMC
- Arviz
- Matplotlib

Install the required dependencies using:

```bash
pip install numpy pandas pymc arviz matplotlib
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/Moeez-Muslim/Linear-Regression-Models-for-Iris-Dataset.git
```

2. Navigate to the project directory:

```bash
cd Linear-Regression-Models-for-Iris-Dataset
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook linear_regression_iris.ipynb
```

4. Explore the analysis and results in the notebook.

## Results

The R-squared values suggest that Model 1 (using petal length) provides a better fit to the data compared to Model 2 (using sepal length).

## Contributors

- Your Name <mail2moeezmuslim@gmail.com>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
