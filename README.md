# Junior Data Scientist Case Study: PFM & Churn Analysis

## Overview

This project tackles a case study for a Junior Data Scientist position. It involves analyzing a transactional dataset from a digital bank to deliver two main outcomes:
1.  **Personal Financial Management (PFM) Analytics:** A deep dive into customer spending and cashflow patterns to uncover insights that could be used in a banking app.
2.  **Customer Churn Prediction:** A baseline machine learning model to predict whether a customer will churn in the next 30 days.

## Project Structure

### Core Files
*   **`pfm_churn_case_study_transactions.csv`** - Raw transaction data (customer demographics, transaction details, churn labels)
*   **`pfm_analytics.ipynb`** - PFM insights notebook with data cleaning, EDA, and customer behavior analysis
*   **`churn_model.ipynb`** - Churn prediction notebook with feature engineering, model training, and evaluation
*   **`requirements.txt`** - Python dependencies for the project


## Setup Instructions

### Prerequisites

- **Python 3.8 or higher** (tested with Python 3.9+)
- **pip** package manager
- **Jupyter Notebook** or **Jupyter Lab** (or an IDE with Jupyter support like VS Code)

### Installation Steps

1. **Clone or download this repository** to your local machine

2. **Navigate to the project directory:**
   ```bash
   cd D:\JDS
   ```

3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

   This will install:
   - `pandas` - Data manipulation and analysis
   - `numpy` - Numerical computing
   - `scikit-learn` - Machine learning models and evaluation
   - `matplotlib` - Data visualization
   - `seaborn` - Statistical data visualization

### Running the Analysis

1. **Start Jupyter:**
   ```bash
   jupyter notebook
   # or
   jupyter lab
   ```

2. **Open and run notebooks in order:**
   - **First:** `pfm_analytics.ipynb` - PFM insights and customer behavior analysis
   - **Second:** `churn_model.ipynb` - Churn prediction model training and evaluation

3. **Execute cells sequentially:**
   - Run cells from top to bottom using `Shift + Enter`
   - Each notebook is self-contained and performs its own data cleaning

**Note:** Both notebooks can be run independently. They each load and clean the raw data from scratch.

## Expected Outputs

### PFM Analytics Notebook (`pfm_analytics.ipynb`)

**Key Outputs:**
- **Customer Cashflow Summary** - Aggregated inflow, outflow, and net cashflow per customer
- **Top 10 Spending Categories** - Horizontal bar chart showing highest spending categories
- **Transaction Activity Heatmap** - Day × Hour heatmap showing peak transaction times
- **Recurring Payments Detection** - Count of potential monthly recurring payments (rent, utilities, subscriptions)

## Viewing the Presentation

### HTML Presentation (Recommended)

1. **Open in browser:**
   - Double-click `presentation.html` to open in your default browser
   - Or right-click → "Open with" → Choose your browser

