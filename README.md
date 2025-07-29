# stock-market-etl-gcp
ETL pipeline using Python and BigQuery to analyze Indian stock data

This is a simple ETL pipeline project that:

- **Extracts** Reliance stock data from a CSV file (`reliance_stock.csv`)
- **Transforms** the data using basic cleaning and formatting
- **Loads** the cleaned data into a Google BigQuery table

### Files

- `extract_transform.py`: Handles extraction and transformation
- `load_to_bigquery.py`: Loads data into BigQuery
- `reliance_stock.csv`: Sample stock data
- `gcp_key.json`: Service account key
- `requirements.txt`: Project dependencies

### How to Run

1. Create a BigQuery dataset and table.
2. Set up your service account and save the key as `gcp_key.json`.
3. Install dependencies:


pip install -r requirements.txt
