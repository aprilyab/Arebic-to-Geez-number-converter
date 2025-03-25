# Convert Arabic Numbers to Geez (Ethiopian Numerals)

This Python script allows you to convert an Arabic number (standard numerical system) into Geez numerals, which are used in Ethiopia. The function `convert_to_geez()` accepts an integer and returns its representation in Geez numerals.

## Function Overview

### `convert_to_geez(num)`
This function takes an integer input and converts it into its Geez numeral representation. It supports converting numbers from 1 to 100,000 and possibly beyond, depending on future extensions. The script also handles various number ranges such as units, tens, hundreds, thousands, and ten-thousands.

### Helper Functions:
- **`number(num)`**: Converts individual numbers like 1, 2, 3, etc., into their Geez equivalent.
- **`unit(num)`**: Converts the unit (ones) digit to Geez.
- **`tenth(num)`**: Converts the tens digit to Geez.
- **`hundred(num)`**: Converts the hundreds place to Geez.
- **`thousend(num)`**: Converts the thousands place to Geez.
- **`ten_thousend(num)`**: Converts ten-thousands place to Geez.

## Installation

1. Ensure that Python is installed on your system.
2. Download the script or copy the code into your Python file.

## How to Use

1. Save the Python code into a `.py` file (e.g., `geez_converter.py`).
2. Run the script.
3. Input an Arabic number when prompted.

Example:
```bash
$ python geez_converter.py
enter a arabic number to be changed to GEEZ number: 12345
፲፻፲፪፩
