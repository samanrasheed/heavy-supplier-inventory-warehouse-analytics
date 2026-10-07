# Heavy Supplier, Inventory & Warehouse Analytics

## Project Overview

This Data Science project analyzes supplier performance, inventory health,
warehouse operations, procurement activity, sales, and customer behavior.

The goal is to identify operational inefficiencies, improve inventory
management, evaluate supplier reliability, and support data-driven decisions.

## Project Objectives

- Profile and validate datasets
- Clean and integrate business data
- Analyze product and inventory performance
- Evaluate warehouse efficiency
- Assess supplier and procurement performance
- Analyze customer purchasing behavior
- Develop forecasting and risk analysis
- Create visualizations and business recommendations

## Datasets

The project uses 12 CSV datasets:

- branches
- customers
- inventory_master
- invoices
- payments
- products
- purchase_orders_header
- purchase_orders_lines
- sales_orders_header
- sales_orders_lines
- stock_ledger
- suppliers

Raw datasets may be kept separately if they are too large or restricted
for public distribution.

## Project Structure

- `data/` - Dataset instructions and data files, when appropriate
- `notebooks/` - Jupyter notebooks for analysis
- `outputs/` - Charts, tables, and exported results
- `requirements.txt` - Python dependencies

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab
- Scikit-learn (for planned predictive analysis)

## Progress

### Phase 1: Data Foundation & Preparation

- Initial profiling of 12 datasets
- Checked row counts, columns, missing values, and exact duplicate rows
- Found 2,370 missing values in `purchase_orders_header.received_date`
- Initial investigation showed these missing dates belong to cancelled purchase orders

Further validation and analysis will be documented as the project develops.

## How to Run

1. Clone or download this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Place the required CSV datasets in the `data/` directory, if permitted.
4. Open the notebooks in Google Colab or Jupyter Notebook.
5. Update dataset paths if necessary.

## Author

Saman Rasheed
