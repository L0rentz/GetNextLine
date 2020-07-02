# GetNextLine

- **Language:** C
- **Group Size:** 1

## Goal

The goal of this project is to write a function that returns a read line from a file descriptor.  
If there are no more lines to return, or if there is an error during the reading, the function will come back
NULL.  
  
You must define a macro called READ_SIZE in your get_next_line.h file, which indicates the amount of characters to be read for each read() call.

## Authorized functions

read, malloc and free.
