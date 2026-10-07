# End-to-End Fraud Detection System

Jupyter notebook pipeline for credit card fraud detection on the [ULB MLG credit card fraud dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) (European transactions, September 2013).

## Contents

- `FD_System.ipynb` — problem framing, EDA, baselines, logistic regression, random forest, and tuned XGBoost with ROC/PR metrics.

## Setup

1. Clone this repository.
2. Create a virtual environment and install dependencies:

   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   pip install pandas matplotlib scikit-learn xgboost jupyter
   ```

3. Download `creditcard.csv` from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and place it in the project root (same folder as the notebook).

4. Open and run the notebook:

   ```bash
   jupyter notebook FD_System.ipynb
   ```

## Data

The dataset is not included in this repository due to size and licensing. You must obtain it from Kaggle and agree to their terms.

## License

Notebook and documentation in this repo are provided as-is for portfolio and learning purposes. The underlying transaction data remains subject to Kaggle/dataset terms.
