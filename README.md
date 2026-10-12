# Heavy Supplier, Inventory & Warehouse Analytics

## Project Overview
A Data Science internship project focused on supplier performance,
inventory management, warehouse operations, procurement, sales, and customer analytics.

## Objectives
- Profile and validate business datasets
- Clean data and document quality checks
- Integrate related datasets for analysis
- Analyze inventory, products, and warehouse performance
- Evaluate supplier and procurement performance
- Analyze customer behavior
- Develop forecasting, risk analysis, and business recommendations

## Datasets
The project uses 12 datasets covering suppliers, branches, customers,
products, inventory, purchase orders, sales orders, invoices, payments,
and stock movements.

## Project Structure
- `notebooks/` - Analysis notebooks
- `outputs/` - Cleaning logs, reports, and visualizations
- `data/` - Local datasets; raw data is excluded from Git where appropriate
- `requirements.txt` - Python dependencies

## Progress
### Phase 1: Data Foundation & Preparation
- Completed initial profiling of 12 datasets
- Investigated missing values and duplicate rows
- Validated primary/composite keys and foreign-key relationships
- Converted date columns to datetime
- Checked date consistency, numeric values, categorical values,
  and inventory stock-level rules
- Documented data-quality findings

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab

cat > .gitignore <<'EOF'
# Raw datasets
/data/
*.zip

# Python and notebook temporary files
__pycache__/
*.py[cod]
.ipynb_checkpoints/
.DS_Store

# Environment and secrets
.env
.venv/
