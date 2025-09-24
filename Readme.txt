# Harry Potter MapReduce Assignment

# Project Overview
This project implements a simple "MapReduce" pipeline in Python to analyze text from the *Harry Potter* books.  
The assignment required:
1. Extracting two text files (`file1.txt` and `file2.txt`) from a combined Harry Potter PDF based on birth date rules.
2. Running MapReduce code to:
   - Count the frequency of each word in `file1.txt`.
   - Identify and count non-English words (names, places, spells, etc.) in `file2.txt`.

# Files in this Repository
- Code and Output.ipynb - contains code for extracting data from "Harry Potter" book
- Code and Output.ipynb - contains MapReduce implementation, and outputs.
- file1.txt - 10 pages extracted from Book 5 starting at page 15 (DOB day rule).
- file2.txt - 10 pages extracted from Book 5 starting at page 100 (DOB year rule).
- words.txt - dictionary of common English words used to filter out non-English terms in `file2.txt`.

Note: The Harry Potter book is not included but the file 1 and file 2 has all the necessary data from the story book.