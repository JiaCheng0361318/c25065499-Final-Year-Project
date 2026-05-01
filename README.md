This is the Final Year Project ( Cardiff University Bachelor of Computer Science) 
Author: Wong Jia Cheng 25065499
Supervisor: Xianfang Sun



# Stock Prediction Model Training and Evaluation

This repository contains the Jupyter Notebooks and datasets used for training, evaluating, and backtesting the stock prediction models (including BiLSTM and Attention-based architectures).

## Contents

- **Notebooks**: Scripts for training (`trainV1.ipynb`, `trainV2.ipynb`, etc.), evaluating models (`evaluation.ipynb`), and running market simulations (`backtest.ipynb`).
- **datasets/**: Stock market data used for training and testing the models.
- **models/**: All of the model .pth trained.
- **results/**: All of the evaluations results files.
- **Master_Methodology_Metrics.csv**: Consolidated performance metrics across different architectures.

## Setup

1. Create a virtual environment and activate it.
2. Install the necessary dependencies (e.g., PyTorch, pandas, scikit-learn).
3. Run the notebooks starting with the `train` prefixed files to train the models, followed by `evaluation.ipynb` and `backtest.ipynb`.
