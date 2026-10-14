# Linear Regression from Scratch Using Gradient Descent

## Overview
This notebook implements a simple linear regression model in Python and trains it using gradient descent. It learns the weight (`w`) and bias (`b`) for the linear equation:

\[
\hat{y} = wx + b
\]

The notebook uses a small sample dataset and visualizes the observed data points alongside the fitted regression line using Matplotlib.

## Dataset
The notebook defines eight input values and corresponding target values directly in the code:

- `X = [1, 2, 3, 4, 5, 6, 7, 8]`
- `Y = [2.9, 3.1, 4.0, 5.2, 6.1, 7.3, 8.0, 9.1]`

This is a small example dataset included in the notebook; it is not an external dataset.

## How it works
1. Initialize weight and bias to `0.0`.
2. For each epoch, calculate predictions using `y_pred = w*x + b`.
3. Calculate gradients for weight and bias from the prediction errors.
4. Update the weight and bias using the learning rate.
5. Plot the data points and the fitted line.

## Implementation details
- **Language:** Python
- **Algorithm:** Batch gradient descent
- **Learning rate:** `0.01`
- **Epochs:** `100`
- **Visualization:** Matplotlib

The `GD()` function returns the learned weight and bias. The `main()` function calls gradient descent and displays a scatter plot of the actual points and the fitted regression line.

## Requirements
- Python 3
- Jupyter Notebook
- Matplotlib

Install Matplotlib if needed:

```bash
python -m pip install matplotlib
```

## Run the notebook
1. Open `linearRegression.ipynb` in Jupyter Notebook or VS Code with the Jupyter extension.
2. Run the cells in order.
3. The notebook prints the learned weight and bias, then displays the regression plot.

## Files
- `linearRegression.ipynb` — notebook containing the implementation and visualization.
- `README.md` — project description and instructions.
- `requirements.txt` — Python dependency.

## Scope
This project demonstrates the basic mechanics of linear regression and gradient descent on a small, manually specified dataset. It does not include a separate train/test split or evaluation metrics.
