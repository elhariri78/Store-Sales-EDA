# Store-Sales-EDA

This project focuses on **Exploratory Data Analysis (EDA)** of store sales data. The goal is to understand the underlying patterns in the data, identify trends, and derive insights to improve sales and performance.



## Introduction

In this project, we perform **Exploratory Data Analysis (EDA)** on a dataset of store sales. The analysis helps uncover patterns, trends, and relationships between various features such as:
- Sales trends over time
- Impact of promotions on sales
- Analysis of different store types
- Comparison of sales across different regions and categories

The insights gained from this analysis can be used for better decision-making to improve sales performance.

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/elhariri78/Store-Sales-EDA.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Store-Sales-EDA
    ```

3. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

4. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

## Dataset

- The dataset used in this project contains sales data of various stores.
- Download the dataset from [https://www.kaggle.com/code/elmuatazelhariri/store-sales-eda](#) or provide your own dataset and place it in the `data/` directory.
  
**Sample of the dataset columns:**
- `Store`: Unique ID of the store
- `Date`: Date of the transaction
- `Sales`: Total sales for the day
- `Customers`: Number of customers
- `Promo`: Whether a store was running a promotion on that day
- `StateHoliday`: Indicates a state holiday (if applicable)
- `SchoolHoliday`: Whether the day was a school holiday

## Usage

1. Make sure the dataset is placed in the `data/` directory.
2. Run the Jupyter notebook to perform the EDA:

    ```bash
    jupyter notebook
    ```

3. Open the `store_sales_eda.ipynb` notebook and run the cells.

Alternatively, you can run the analysis via the Python script:

```bash
python analyze_sales.py
