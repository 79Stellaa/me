TODO: Reflect on what you learned this week and what is still unclear.
the file open modes：
"r": Read mode (default mode).
"w": Write mode. If the file exists, it will be cleared. If the file does not exist, a new file will be created.
"a": Append mode. If the file exists, data written will be appended to the end of the file. If the file does not exist, a new file will be created.
"r+": Read and write mode.

“..” indicates the parent directory of the current directory. This is a special symbol used to navigate to the parent directory.
“ ../x” means to find or create x files in the parent directory of the current directory.
Without the “..” symbol, it means to find or create a file named x in the current directory.

“with open(...) as ... Structure”: A context manager in Python ensures that the file is automatically closed after the code block is executed, either normally or because of an exception.

“encoding="utf-8" using UTF-8 encoding to process text data in the file.

import json : Imports the json module so that you can use the functions in the module.
json.dumps() : is a function in the json module that converts a Python object to a JSON-formatted string.

json.loads(): Convert a JSON string back to a Python object.
json.dump(): Convert a Python object to a JSON string and write it to a file.
json.load(): Read JSON data from a file and convert it to a Python object.


open()，write(): two functions that accept different parameters in their parentheses.
The open() function is used to open a file. The following parameters can be included in the brackets:
   file (necessary)：
       The path of the file, type is string. "example.txt"
   mode (optional)
   buffering (optional)：
       Controls file buffering, integer type. Can be set to 0 (no buffering), 1 (line buffering), or an integer greater than 1 (specifying the buffer size).
   encoding (optional)：
       The encoding type of the file, usually used when reading or writing text files, such as "utf-8"
   errors (optional)：
       Set error handling method, such as "strict", "ignore", "replace", etc.
   newline (optional)：
       Controls newline character processing, commonly used in text files, such as None, '', '\n', '\r', '\r\n'
write() 
   string (necessary):
       Indicates the content to be written to the file, the type is string.

