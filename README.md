
## Overview
This script reads lines from a specified text file, encodes them into a specified encoding format, decodes them back, and prints both the byte string and the decoded string. It is designed to demonstrate how text encoding and decoding work in Python.

## Prerequisites
- Python 3.x

## Usage
To run the script, use the following command in your command prompt or terminal:
```
python main.py <input_encoding> <error_handling>
```

For example, if you want to use `utf-8` encoding and have a file named `textfile.txt`, you would run:
```
python main.py utf-8 textfile.txt
```

## Parameters
- `input_encoding`: The encoding format to use for encoding and decoding the text.
- `error_handling`: The error handling scheme to use (`strict`, `ignore`, `replace`, etc.).
- `textfile.txt`: The name of the text file containing the lines of text to be processed.



## Script Breakdown

### `main` Function
The `main` function reads lines from the text file and processes each line by calling `print_line`. It uses recursion to read and process each line until the end of the file.

### `print_line` Function
The `print_line` function:
1. Strips the line of any leading/trailing whitespace.
2. Encodes the line using the specified encoding.
3. Decodes the byte string back into a string.
4. Prints the byte string and the decoded string in a formatted manner.

## Note
Make sure the text file you are using (`textfile.txt`) exists in the same directory as the script or provide the correct path to the file.

