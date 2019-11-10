1.Which command walks a file hierarchy in search of a keyword?  
`find`  
For example, search for all `.c` files in current directory and all sub directories, use `find . -name "*.c"`.  
  

2.Which command displays information about processes running on your machine?  
`top`  
  

3.Which command terminates a process?  
Find the process id of a process, and use `kill $id`  
  

4.Which command can help you find the difference between two files  
One can use `cmp` and `diff` to compare two files.  
`cmp` compares files character by character and returns position of first different character.  
`diff` compares files line by line and returns all different lines.