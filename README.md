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
   git clone <repository_url>
   cd secret_santa_project
