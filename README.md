# GET_Next_Line
This project is a function that reads one line at the time from a given text file. The line should be ending by '\n' 
newline character so it can move forward for the next line. The function reads a line from given file descriptor and saves it to the variable "line". 
Function returns 1 if a line has been read, 0 when reading has been completed and -1 in case of an error.  
## Installation  
1. git clone https://github.com/damzkii/GET_Next_Line  
2. in the root cd libft (libft folder)  
3. make all (in the libft folder)  
4. cd .. (back to get_next_line root)  
5. gcc main.c get_next_line.c libft/libft.a  
6. ./a.out (returns the bible.txt for test)  
## Why?
This function is a simple and challenging project which allows you to learn deeply about open(), read() and close() 
functions as well as static variables and file descriptors. I've updated my libft library and added this function there
and used it on future projects like **FDF-Project**.
