# excel-divider-script

## About
A simple Python script for dividing large Excel files into multiple smaller files. Takes an Excel file and divides it into multiple files of a user-specified number of rows and a user-specified number of header rows. Will number the new files in their names, adding the number to the name of the original file.

## How to Use
Make sure you have Python installed and the script is marked as executable.

Install dependencies using:
```
pip install -r requirements.txt 
```

Run the script using:
```
./excelScript.py <path_of_excel_file> <num_header_rows> <num_non_header_rows_per_file>
```
