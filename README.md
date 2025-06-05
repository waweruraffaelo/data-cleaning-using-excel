# data-cleaning-using-excel
# Data Cleaning and Preparation (Excel-based)

This repository serves as a guide and central location for the data cleaning and preparation process using Microsoft Excel. The goal is to transform raw, potentially inconsistent data into a clean, unified, and analysis-ready format.

## Project Overview

The data cleaning process will be performed entirely within Microsoft Excel, focusing on the following key steps:

1.  **Data Truncation and Transformation**: Restructuring rows into a columnar format to improve data organization and accessibility within Excel.
2.  **Data Type Conversion**: Manually adjusting cell formats in Excel to ensure all columns have appropriate data types (e.g., General, Number, Text) for accurate filtering and sorting.
3.  **City Name Standardization**: Renaming inconsistent city entries to a standardized format. This will involve using the provided `clean_name.txt` file as a reference to manually or semi-automatically update city names within Excel (e.g., using find/replace or VLOOKUP if applicable). This addresses variations like "Big Apple-Las Vegas" or "Vegas-Las Vegas" by mapping them to their official city names[cite: 1].
4.  **Dataset Merging**: Combining two distinct datasets into a single, comprehensive dataset within Excel (e.g., using copy-paste, or advanced features like Power Query if comfortable).

## Repository Contents

* `clean_name.txt`: A reference file containing a list of standardized city names and their common variations, used for renaming operations[cite: 1].
* `data/`: (Planned) This directory will store the raw input datasets (e.g., `.xlsx`, `.csv` files).
* `output/`: (Planned) This directory will store the cleaned and merged output dataset in Excel format.
* `documentation/`: (Optional, but recommended) This directory could contain screenshots or detailed steps of the Excel cleaning process.

## Getting Started

### Prerequisites

* Microsoft Excel (2013 or newer recommended for full functionality)

### Usage

1.  **Download/Clone Repository**: Obtain the contents of this repository to your local machine.
2.  **Place Raw Data**: Put your raw input datasets (e.g., `dataset1.xlsx`, `dataset2.csv`) into the `data/` directory.
3.  **Open `clean_name.txt`**: Keep this file open as a reference for standardizing city names[cite: 1].
4.  **Perform Cleaning in Excel**:
    * Open your raw data files in Excel.
    * Apply the data truncation, type conversions, and city name standardizations as planned.
    * Merge the two datasets into a single Excel workbook or sheet.
5.  **Save Cleaned Data**: Save your final, cleaned, and merged dataset into the `output/` directory (e.g., `cleaned_merged_data.xlsx`).

## Contributing

As this project primarily uses Excel, contributions can include:

* Suggestions for more efficient Excel formulas or techniques for data cleaning.
* Improved documentation or screenshots of the Excel process.
* Updates to the `clean_name.txt` file if more variations are discovered.

## License

(Optional: Choose a license and add its details here, e.g., MIT, Apache 2.0)

## Contact

For any questions or inquiries, please contact [Your Name/Email].
