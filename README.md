# EDA & Classification — German Credit Risk Dataset

---

> My first data science project

We will use Dr. Hans Hofmann’s “credit-g” dataset, available on OpenML. Our goal is to accurately predict credit risk and defaults so that banks can minimize losses. We will perform exploratory data analysis (EDA), then preprocess the data, and train and evaluate models such as logistic regression and random forests.

---

## Project Structure
```
├── data/
│   ├── raw/
│   └── preprocessed/
├── models/
│   └──preprocessor.joblib
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_modeling.ipynb
├── outputs/
│   └── figures/
├── main.ipynb
└── requirements.txt
```

---

## Notebooks
| # | Notebook | Description |
|---|----------|-------------|
| 1 | EDA | Distribution analysis, correlations, class balance |
| 2 | Preprocessing | Encoding, scaling, train/test split |
| 3 | Modeling | Model comparison, metrics, feature importance |

---

## Results
(Soon)

---

## Setup
pip install -r requirements.txt

---

## Dataset
[Link to UCI German Credit dataset / OpenML credit-g](https://www.openml.org/search?type=data&sort=version&status=any&order=asc&exact_name=credit-g&id=31)
