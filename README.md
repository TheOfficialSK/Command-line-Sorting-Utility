# Command Line Sorting Utility
## Overview
The Command Line Sorting Utility is a versatile tool designed to efficiently process and sort large datasets containing textual and numeric data. With its easy-to-use interface and powerful sorting capabilities, users can make sense of large amounts of data, analyze it, and uncover valuable insights.

This utility is ideal for data analysts, researchers, and anyone who wants to understand their datasets better. It supports various input formats, allowing users to easily integrate it into their workflow.

## Key Features
Process textual and numeric data
Sort data by size or frequency
Perform calculations on the data to reveal insights
Handle a variety of input formats, including files and standard input
Easily manage and explore datasets with a user-friendly command-line interface
Usage
To start using the Command Line Sorting Utility, you'll need to run it from your terminal or command prompt, providing the necessary flags and input files.

## Optional Flags
```-sortingType```: Set the sorting method (either ```natural``` or ```byCount```)

```-dataType```: Set the data type for sorting (either ```long```, ```word```, or ```line```)

```-inputFile```: Specify the input file containing the data to be sorted (**followed by the file path**)

```-outputFile```: Specify the output file where the sorted data will be written (**followed by the file path**)

These flags can be used in tandem when running the program.

### Example
To sort a file containing numbers in ascending order, you would run the following command:

```
java SortingTool -sortingType natural -dataType long input.txt
```
This command will sort the data in the input.txt file using natural sorting and considering the data type as long (numeric).

```
java SortingTool -sortingType natural -dataType long -inputFile input.txt -outputFile output.txt
```
This command will read the data from the input.txt file, sort it using natural sorting and considering the data type as long (numeric), and then write the sorted data to the output.txt file.
