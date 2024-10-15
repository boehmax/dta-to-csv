# DTA to CSV Converter

This repository contains a Python script `DTAtoCSVconv.py` that converts DTA files to CSV format.

## Requirements

- Python 3.x

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/DTAtoCSVconv.git
    cd DTAtoCSVconv
    ```

2. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To convert a DTA file to CSV, run the script with the input DTA file and the desired output CSV file as arguments:
```sh
python DTAtoCSVconv.py -i <inputfolder> -o <outputfolder> -a
```
### Command Line Options
-i <inputfolder>: Specifies the input folder containing the .DTA files.
-o <outputfolder>: Specifies the output folder where the converted .csv files will be saved.
-a: Processes all .DTA files in the specified input folder.

This will process all `.DTA` files in the specified input folder and convert them to `.csv` files in the specified output folder.

## Example
To convert all DTA files in the `input` folder to CSV files in the `output` folder:

```sh
python DTAtoCSVconv.py -i input -o output -a
```

