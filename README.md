# WooStockSync
This project is a Python middleware script that prepares daily import files  for updating stock levels on a WooCommerce webshop.
> **Note:** This is a work-in-progress (beta) version of the script.
> Functionality is still under development and updates are ongoing.

## Goal
- Automatically detect changes in warehouse inventory (Lager.xlsx) 
  compared to webshop stock (wc-product-export.csv)
- Recalculate stock and prices based on unit conversions and client-specific rules
- Filter products by brand as requested by the client
- Generate a clean import file ready for upload to WooCommerce

## Tools
- Python (pandas) for data processing
- Excel / CSV files as data sources
- GitHub for version control and portfolio display
