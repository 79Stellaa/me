TODO: Reflect on what you learned this week and what is still unclear.
the file open modes：
"r": Read mode (default mode).
"w": Write mode. If the file exists, it will be cleared. If the file does not exist, a new file will be created.
"a": Append mode. If the file exists, data written will be appended to the end of the file. If the file does not exist, a new file will be created.
"r+": Read and write mode.

“..” indicates the parent directory of the current directory. This is a special symbol used to navigate to the parent directory.
“ ../x” means to find or create x files in the parent directory of the current directory.
Without the “..” symbol, it means to find or create a file named x in the current directory.

“with” statement：A context manager that ensures that the file is properly closed after the operation is completed.