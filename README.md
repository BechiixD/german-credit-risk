# EDA & Classification — German Credit Risk Dataset

We will use Dr. Hans Hofmann’s “credit-g” dataset, available on OpenML. Our goal is to accurately predict credit risk and defaults so that banks can minimize losses. We will perform exploratory data analysis (EDA), then preprocess the data, and train and evaluate models such as logistic regression and random forests.

## Project Structure
credit-g_eda/
├── data/
│   ├── raw/
│   └── preprocessed/
├── notebooks/
│   ├── 01_eda.ipynb          # Exploratory data analysis
│   ├── 02_preprocessing.ipynb # Feature engineering & cleaning
│   └── 03_modeling.ipynb     # Model training & evaluation
├── outputs/figures/
├── main.ipynb
└── requirements.txt

## Notebooks
| # | Notebook | Description |
|---|----------|-------------|
| 1 | EDA | Distribution analysis, correlations, class balance |
| 2 | Preprocessing | Encoding, scaling, train/test split |
| 3 | Modeling | Model comparison, metrics, feature importance |

## Results
(Soon)

## Setup
pip install -r requirements.txt

## Dataset
[Link to UCI German Credit dataset / OpenML credit-g](https://www.openml.org/search?type=data&sort=version&status=any&order=asc&exact_name=credit-g&id=31)
