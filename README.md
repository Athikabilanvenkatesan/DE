# DE

# Cold Storage Data Analysis

This repository contains a Jupyter Notebook that processes and analyzes cold storage data. The notebook extracts data from a PDF, cleans the data, and visualizes it using maps. The following steps outline the content and functionality of the notebook.


## Steps Performed in the Notebook

### 1. PDF Data Extraction
- The notebook reads data from a PDF file using `pdfplumber` and stores it in a pandas DataFrame.

### 2. Data Cleaning
- Handles missing values.
- Renames columns for clarity.
- Drops unnecessary columns.
- Removes duplicate entries.
- Converts data types to ensure consistency.
- Exports the cleaned data to an Excel file (`cleaned_cold_storage_data.xlsx`).

### 3. Geocoding
- Utilizes the `geopy` library to get latitude and longitude coordinates for cold storage locations.

### 4. Mapping
- Visualizes the cold storage data on a map using `folium`.
- Includes different marker colors or sizes based on the storage capacity.
- Conducts a cluster analysis to identify regions with high concentrations of cold storages.

## Files in this Repository

- `DE.ipynb`: The main Jupyter Notebook containing all code for data extraction, cleaning, and visualization.
- `cleaned_cold_storage_data.xlsx`: The cleaned and processed data exported as an Excel file.

## Requirements

To run the notebook, you will need the following Python packages:

- `pdfplumber`
- `pandas`
- `openpyxl`
- `geopy`
- `folium`

You can install the required packages using pip:

```bash
pip install pdfplumber pandas openpyxl geopy folium.





