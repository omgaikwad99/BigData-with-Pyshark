# Big Data with PySpark

This Jupyter Notebook demonstrates how to perform data analysis and manipulation on a weather dataset using PySpark, a distributed computing framework for big data processing.

## Prerequisites
Before running this notebook, ensure that you have the following prerequisites installed:

- Python 3
- PySpark
- Additional Python libraries: zipfile, os, pandas, tabulate

## Dataset
The dataset used in this notebook contains weather data, including information such as station name, date, temperature, precipitation, and wind measurements. The data is provided in a compressed ZIP file (`data.zip`), which needs to be extracted before running the notebook.

## Notebook Sections
The notebook is divided into several sections, each addressing a specific task or analysis:

1. **Data Extraction:** The notebook starts by installing the PySpark library and extracting the data from the ZIP file into a directory named `data`.
2. **Data Loading:** The weather data is loaded into a PySpark DataFrame from the CSV files in the `data` directory.
3. **Task 1:** Find the hottest day for each year in the dataset.
4. **Task 2:** Find the coldest day for the month of January across all years in the dataset.
5. **Task 3:** Find the maximum and minimum precipitation values for the year 2015, excluding invalid values.
6. **Task 4:** Calculate the percentage of missing wind gust data for the year 2019.
7. **Task 5:** Calculate the mean, median, mode, and standard deviation of the temperature for each month in the year 2020.
8. **Output Generation:** The results from the above tasks are formatted and written to a text file named `result.txt`.

## Usage
- Make sure you have the `data.zip` file in the same directory as the Jupyter Notebook.
- Run the notebook cells sequentially to perform the data extraction, loading, and analysis tasks.
- The final output will be written to the `result.txt` file in the same directory as the notebook.

*Note:* The notebook assumes that the `data.zip` file is present in the same directory. If the file is located elsewhere, you will need to modify the `zip_file_path` variable accordingly.
