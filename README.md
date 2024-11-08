# Title :
 
  CSV_Extraction


# Description : 

This program automates the Secret Santa assignment process for a group of employees. It ensures that each employee is assigned a different person to whom they will give a gift, following rules such as avoiding assigning someone their own name or the person they were assigned last year. The assignments are saved to a CSV file for easy sharing and organization.


## Features

- Reads employee and previous assignment data from Excel files.
- Assigns each employee a Secret Santa partner, avoiding the previous year's assignments.
- Saves the assignments to a CSV file.
- Contains unit tests to ensure correctness and reliability of the assignments.


## Requirements

- Python 3.7+
- `pandas` library (for reading/writing Excel and CSV files)
- `openpyxl` library (for reading `.xlsx` files)
- `pytest` (for running unit tests)


## Installation

1. Clone this repository:
   
   git clone https://github.com/vinodkumarkuruva/CSV_Extraction.git
   cd secret_santa_project

   
## Install the required dependencies:

pip install -r requirements.txt

## Usage

Prepare the Input Files:

1 . Create an Excel file for employees, e.g., Employee-List.xlsx, with the following columns :  Employee_Name , Employee_EmailID
2 . Create an Excel file for previous assignments, e.g., Secret-Santa-Game-Result-2023.xlsx, with the following columns :  Employee_Name , Secret_Child_Name (the person they were assigned last year)

## Run the Application :  python secret_santa.py

