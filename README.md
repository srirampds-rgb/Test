[README.md](https://github.com/user-attachments/files/26486868/README.md)
# Supplier Dashboard using Streamlit

This project is a beginner-friendly supplier dashboard built using Streamlit, pandas, and Plotly.

## Overview

The dashboard reads supplier sales data from an Excel file, allows the user to select a supplier, and displays summary metrics and charts for quick analysis.

## Features

- Load supplier data from Excel
- Select a supplier from a dropdown
- Show total sales
- Show average monthly sales
- Show best month sales
- Display monthly sales trend chart
- Display product-wise sales chart
- Show filtered supplier data in table format

## Tech Stack

- Python
- Streamlit
- pandas
- Plotly
- Excel

## Project Files

- `streamlit_supplier_dashboard.py` - Main Streamlit application
- `supplier_details.xlsx` - Sample supplier data for testing
- `screenshot.png` - Dashboard screenshot
- `requirements.txt` - Required Python libraries

## How to Run

1. Install the required libraries:

```bash
pip install -r requirements.txt
```

2. Run the Streamlit app:

```bash
streamlit run streamlit_supplier_dashboard.py
```

3. Open the local URL shown in the terminal, usually:

```text
http://localhost:8501
```

## What this project does

This project demonstrates how to build a simple interactive dashboard in Python without writing frontend code separately.

- Streamlit is used to create the web interface.
- pandas is used to read and filter Excel data.
- Plotly is used to build interactive charts.

## Screenshot

![Supplier Dashboard Screenshot](screenshot.png)

## Future Improvements

- Add file upload option
- Add region filter
- Add month filter
- Compare multiple suppliers
- Add downloadable reports
- Add login/authentication

## Author

Sriram
