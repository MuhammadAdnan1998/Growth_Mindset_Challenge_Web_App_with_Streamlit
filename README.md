# Data Sweeper

## Overview
**Data Sweeper** is a Streamlit-based web application that allows users to transform files between CSV and Excel formats with built-in data cleaning and visualization features. This tool is designed to streamline data processing by enabling users to upload, clean, visualize, and convert files with ease.

## Features
- **Upload Multiple Files**: Supports CSV and Excel file uploads.
- **Data Cleaning**:
  - Remove duplicate entries.
  - Fill missing numeric values with column-wise mean.
- **Column Selection**: Choose specific columns to retain for further processing.
- **Data Visualization**:
  - Generate bar charts for numerical data.
- **File Conversion**:
  - Convert CSV to Excel and vice versa.
  - Download the processed file in the selected format.

## Installation
To run the application locally, follow these steps:

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/data-sweeper.git
   ```
2. Navigate to the project directory:
   ```sh
   cd data-sweeper
   ```
3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the application:
   ```sh
   streamlit run app.py
   ```

## Usage
1. Open the application in a browser.
2. Upload a CSV or Excel file.
3. Perform data cleaning operations if needed.
4. Select specific columns to retain.
5. View the data preview and visualizations.
6. Convert the file to the desired format (CSV or Excel).
7. Download the processed file.

## Requirements
- Python 3.7+
- Streamlit
- Pandas
- OpenPyXL (for Excel processing)

## Contributing
Contributions are welcome! Feel free to submit pull requests or report issues.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or support, please reach out to [adnanshaikh84482@gmail.com].

