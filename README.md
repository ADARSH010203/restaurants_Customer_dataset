# README.md

## Project Overview
Data science/ML competition project with food delivery vendor prediction task. No traditional codebase - pure data analysis project.

## Data Structure
- **Train/**: Training datasets (vendors.csv, orders.csv, train_customers.csv, train_locations.csv)
- **Test/**: Test datasets (test_locations.csv, test_customers.csv)
- **SampleSubmission.csv**: Prediction template format (CID X LOC_NUM X VENDOR,target)
- **VariableDefinitions.pdf**: Data dictionary and feature descriptions

## Key Files
- `vendors.csv`: Vendor information with 54 features including location, category, ratings, hours
- `orders.csv`: Order history with customer/vendor relationships and delivery details
- `train_customers.csv`: Customer demographics and metadata
- `SampleSubmission.csv`: Required output format for predictions

## Commands
No build/test/lint commands - this is a data analysis project. Common data science tools would be:
- `python script.py` (if Python analysis is created)
- `jupyter notebook` (if Jupyter notebooks are used)
- Data exploration typically done in Python

## Data Analysis Notes
- Target variable appears to be vendor selection prediction
- Features include vendor ratings, location data, customer history, order patterns
- Sample submission shows format: customer_id X location_number X vendor_id → binary target
