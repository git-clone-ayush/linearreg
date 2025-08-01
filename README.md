# Simple Linear Regression from Scratch

A minimal implementation of **simple linear regression** (fitting \( y = mx + b \)) using **batch gradient descent** and comparison with the closed-form (least squares) solution. Includes plotting to visualize the fitted line against data.

## Features

- Gradient descent implementation to learn slope (`m`) and intercept (`b`)
- Closed-form solution (normal equation / `np.polyfit`) as a reference
- Mean Squared Error (MSE) loss calculation
- Visualization of data and both fitted lines
- Learning rate tuning and basic divergence detection

## Requirements

- Python 3.8+
- `numpy`
- `matplotlib`
- `pandas`

You can install the dependencies with:

```bash
pip install numpy matplotlib pandas
