# ETL Project Using Python and Excel

## Overview
This project implements an ETL (Extract, Transform, Load) process using Python and Excel. The goal is to extract data from various sources, transform it to meet specific requirements, and load the final output into an Excel spreadsheet.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Data Extraction**: data collection from PDF file and then convert it into image  
- **Data Transformation**: Clean and manipulate data  from image file and further convert this docs file
- **Data Loading**: Save the transformed data into an Excel file. there have three section (Chapter,Section,Hadith)

## Technologies Used
- **Python**: The primary programming language used for this project.
- **Pandas**: For data manipulation and analysis.
- **Regular Expression**: find the expected pattern
- **OCR **: OCR (Optical Character Recognition) in Python allows us to extract text from images

## Installation
To get started with this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/TheReinforce43/ETL_project_using_Python_Excel.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ETL_project_using_Python_Excel
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Update the configuration file with your data sources.
2. Run the ETL script:
   ```bash
   python etl_script.py
   ```
3. Check the output Excel file for the transformed data.

## Contributing
Contributions are welcome! If you have suggestions for improvements or find bugs, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
