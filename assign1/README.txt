Group Members: 
1. Venkata Santosh Naidu Mummidi - A20514071
2. Abhishek Konathala - A20514117
3. Aparnaa Dabbula - A20526777

How to run: 

1. Run 'make clean' in the assign1 directory to remove any previous object files. 
2. Run 'make'.
3. Run 'make run_test' to run test cases. 

Description:

There are 16 functions in storage manager.
Each function helps in doing a specific task associated with Read/write of blocks to and from a file.

1. initStorageManager:
    This function initializes the file pointer and makes it available to use in next blocks

2. createPageFile:
    This function created a pagefile and put the null character to reserve the firstpage.

3. openPageFile:
    It takes in file name as argument and opens the pagefile for further use.

4. closePageFile:
    This function closes an existing pagefile. It throws an error if the given file argument is not found.

5. destroyPageFile:
    It destroys the page file by using remove file function.

6. readBlock:
    
