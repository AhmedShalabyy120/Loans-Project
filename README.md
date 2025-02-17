# FMilestone Project

## Overview

This project focuses on data cleaning and transformation using Python. The dataset consists of financial and customer-related information, covering attributes like customer ID, employment details, income, credit data, and loan information.

## Dataset Summary

The dataset contains **27,030** records with the following key attributes:

- **Customer ID**: Unique identifier for each customer
- **Employment Title & Length**: Information about job title and experience
- **Home Ownership & Annual Income**: Financial standing details
- **Verification Status & Zip Code**: Loan application verification data
- **Funded Amount & Loan Term**: Loan-related financial data
- **Interest Rate & Grade**: Risk assessment features
- **Loan Purpose**: Purpose of the loan, such as debt consolidation

### Sample Data Statistics

- **27030** unique customer records
- **13** distinct loan purposes, with **debt consolidation** being the most common
- **36-month** term loans are more frequent
- **27030** verification status records, with 'Source Verified' being the most common
- **50** unique states represented in the dataset

## Requirements

To run this notebook, ensure you have the following dependencies installed:

```bash
pip install -r requirements.txt
```

Alternatively, install individual dependencies:

```bash
pip install numpy pandas matplotlib seaborn
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/your-repo.git
cd your-repo
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `fmilestone.ipynb` and run the cells sequentially.

## Code Overview

Below are some key snippets from the notebook:

```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```
```python
# Load dataset
df = pd.read_excel('fintech_data_15_64_28996.xlsx')
df.head()
```

## Results

The dataset was cleaned and transformed, focusing on:
- Handling missing values
- Standardizing column formats
- Exploring distributions of key financial metrics

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

Ahmed Shalaby
