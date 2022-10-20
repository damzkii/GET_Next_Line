# GET_Next_Line
This project is a function that reads one line at the time from a given text file. The line should be ending by '\n' 
newline character so it can move forward for the next line. The function reads a line from given file descriptor and saves it to the variable "line". 
Function returns 1 if a line has been read, 0 when reading has been completed and -1 in case of an error.  
## How to test the function  
### Install  
![gitcopy](https://user-images.githubusercontent.com/82960301/196993234-f0542fae-4647-4c7b-8f00-edc899c98868.gif)  
1. git clone https://github.com/damzkii/GET_Next_Line  
![gitclone](https://user-images.githubusercontent.com/82960301/196993282-8cb7033c-a196-415b-af0b-6f83e1eb3b74.gif)  
2. make all  
![makeall](https://user-images.githubusercontent.com/82960301/196993314-4d8e621c-9858-4108-834a-dac44c692a4d.gif)  
### Run  
./get_next_line bible.txt  
  
  
![output](https://user-images.githubusercontent.com/82960301/196993427-c1599531-74bf-4725-8c1b-b6f7ee1ecf3b.gif)
## Why?
This function is a simple and challenging project which allows you to learn deeply about open(), read() and close() 
functions as well as static variables and file descriptors. I've updated my libft library and added this function there
and used it on future projects like **FDF-Project**.
