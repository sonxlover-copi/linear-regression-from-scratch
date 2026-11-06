# Linear Regression from Scratch

A compact implementation of linear regression that connects the math to working NumPy and PyTorch code.

## What it covers

- Mean squared error and its analytical gradient
- Numerical gradient checks against the analytical result and PyTorch autograd
- Full-batch and mini-batch gradient descent
- Validation metrics and a short comparison of training behavior

## Run locally

Python 3.10 or newer is recommended. Create an environment and install the dependencies:

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
python -m pip install -r requirements.txt
jupyter lab
```

Open `linear_regression.ipynb` and run all cells. The notebook generates its own small synthetic dataset; no external files are needed.

## Validation

The gradient checks agree across numerical differentiation, the analytical formula, and autograd. The final validation MSE is about 0.225 for both full-batch and mini-batch training in the recorded run.

## Attribution

This is an adapted solution to an educational laboratory. The original assignment and its course attribution are preserved in the notebook.
