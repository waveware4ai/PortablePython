# PortablePython
It provides Portable Python based on Windows and Linux Ubuntu22.  
Python is generally tightly coupled with the system, which makes it difficult for users to use it as they wish (especially in the case of Linux distributions).  
So, I thought that there was a need to create a Python distribution that could be unpacked and run regardless of the path, that would only be added inside the PortablePython directory when adding packages,  
and that would also work on other systems just by compressing and distributing the applications that work based on PortablePython.

Additionally, you can create the most convenient environment possible when using it with zimport/SandBox4Linux at the link below.  
https://github.com/waveware4ai/zimport  
https://github.com/waveware4ai/SandBox4Linux

Installation
------------
1. This portable python can be unpacked and run in any path.
2. Since this portable python does not include any packages, you must first install pip using the python command below.
```
./python ./python.pip.py 
```
Support
------------
Currently, 
PythonPortable Linux version only supports Ubuntu 22, and Python 3.9, 3.10, 3.11, and 3.12 versions were compiled for portable use.  
PythonPortable Windows version has made Python 3.10, 3.11, and 3.12 portable, and has modified it using the already publicly available Python Embedded.  
See the links below  
https://www.python.org/downloads/source/  
https://www.python.org/downloads/windows/  

Compile How to
------------
Perform compile by referencing the script folder
