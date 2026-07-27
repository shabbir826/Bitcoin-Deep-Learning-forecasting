# Deep Learning for Financial Time-Series: Bitcoin Price Forecasting

A unified, modular deep learning pipeline developed as part of an MS Computer Science thesis. This project benchmarks advanced deep learning architectures against traditional statistical models for short-term Bitcoin price prediction.

## Project Overview
This repository contains the master codebase for evaluating a strictly defined baseline of 24 forecasting models. The framework is designed to be highly modular and flexible, ensuring clean code and avoiding redundancy. It includes the implementation and comparison of state-of-the-art architectures such as **Bi-LSTM, TimeXer, TimeMixer, and KOOPA** (Note: the xLSTM architecture is intentionally excluded from this specific experimental baseline).

## Key Features
- **Modular Pipeline:** Train, test, and evaluate any of the 24 models using a single, optimized training loop.
- **Easy Configuration:** Switch between different deep learning and statistical models effortlessly by updating just one parameter in **Cell 2** of the notebook.
- **Comprehensive Benchmarking:** Features advanced preprocessing, rigorous accuracy evaluations, and automated ranking mechanisms optimized for financial time-series data.

## How to Use & Train Models
1. Open the master notebook (`.ipynb` file) in **Google Colab**.
2. Mount your Google Drive to load the historical Bitcoin dataset, or upload the dataset directly to the Colab environment.
3. Navigate to the **Configuration Section (Cell 2)**.
4. Update the model selection variable to your target architecture (e.g., `model_name = 'KOOPA'` or `'TimeMixer'`).
5. Run the remaining cells to execute the data pipeline, train the selected model, and output the forecasting accuracy metrics.

## Author Profile
**AI Researcher | Deep Learning for Financial Time-Series | Systematic Literature Reviews**
