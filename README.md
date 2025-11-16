# Accident Risk Prediction Project

Machine learning project for predicting road accident risk based on simulated road accident data from Kaggle.

## Project Structure
```
project/
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── sample_submission.csv
├── notebooks/
│   └── accident_risk_analysis.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## Setup & Installation

### 1. Clone/Download the project
```bash
git clone <your-repo-url>
cd accident-risk-prediction
```

### 2. Create virtual environment
```bash
# Create venv
python -m venv venv

# Activate (Windows)
venv\Scripts\activate

# Activate (Mac/Linux)
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```
Then open `notebooks/accident_risk_analysis.ipynb` and select venv as kernel

## Dataset

The dataset comes from a Kaggle competition and contains:
- **train.csv** - training data with `accident_risk` target (continuous values 0-1)
- **test.csv** - test data for predictions
- **sample_submission.csv** - submission format example

Dataset was generated from a deep learning model trained on the Simulated Roads Accident dataset.


## Project Goals

1. Exploratory Data Analysis (EDA)
2. Feature engineering and preprocessing
3. Building predictive models
4. Model evaluation and comparison
5. Generating predictions for test set

