# Data_Mining_Exam

## Project Overview
This repository contains the complete Jupyter Notebook and dependencies for the Olist Brazilian E-Commerce analysis. The project covers data preparation, market basket analysis, seller segmentation, anomaly detection, and predictive modelling for late deliveries.

## Repository Structure
- `Data_mining_exam.ipynb`: The main Python Jupyter notebook containing all code and analysis.
- `dependency_file.txt`: The Python dependencies required to run the notebook.
- `data/`: Folder where the dataset files should be placed (see instructions below).

## How to Run This Notebook

**1. Install Dependencies**
Ensure you have Python installed. Open your terminal/command prompt and run:
```bash
pip install -r dependency_file.txt

2. Download the Data (IMPORTANT)
Because the Olist dataset is large (the geolocation file exceeds GitHub's 100MB limit), the CSV files are not hosted directly in this repository.

Download the dataset from Kaggle: Brazilian E-Commerce Public Dataset by Olist

Extract the zip file.

Create a folder named data in the root of this repository.

Move all 9 CSV files into the data/ folder.
├── Data_mining_exam.ipynb
├── dependency_file.txt
├── README.md
└── data/
    ├── olist_customers_dataset.csv
    ├── olist_geolocation_dataset.csv
    ├── olist_order_items_dataset.csv
    ├── olist_order_payments_dataset.csv
    ├── olist_order_reviews_dataset.csv
    ├── olist_orders_dataset.csv
    ├── olist_products_dataset.csv
    ├── olist_sellers_dataset.csv
    └── product_category_name_translation.csv
3. Execute the Notebook
Open Data_mining_exam.ipynb in Jupyter Notebook or JupyterLab.
Click Kernel -> Restart & Run All to execute the notebook from top to bottom.

