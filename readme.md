```
"""
TASK: Given a data file filled with integers, stream through the data file, and find all lines
that end in the given SUFFIX.
Whenever such a line is found, run the given slow_function on it and the 10 lines before and after
this line (21 lines in total), and sum the results. Write all such sums to the given output path
in the same order that the SUFFIX-bearing lines appear. You may assume that the first 10 lines and
last 10 lines do not end in SUFFIX.
The file should be streamed through quickly, and you may not keep the entire file contents in
memory. Your solution should be compatible with an indefinitely long data file, and your solution
should read through the file only once.
After reading through the file, you must output to stdout (print) the number of lines you found,
which should match the line count of your output file (give or take an extra '\n' at the end).
Your program should exit gracefully at the end of all processing, and will be judged based on
correctness, coding style, and time taken to output the line count. The expected output file has
been provided for this sample input to double check your work.
Our reference solution took 0.11 seconds on average to get line count (on a 2019 Macbook Pro with
a 2.6GHz Intel Core i7 processor).
"""
```