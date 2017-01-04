#The case is to describe how to create and import a custom C library in Python (Linux). 
The original article is form here http://www.dreamincode.net/forums/topic/252650-making-importing-and-using-a-c-library-in-python-linux-version/
    1. We begin by writing some C code we want to compile into a library. 
    2. Compile it to a share library with so extension 
```Bash
gcc -Wall -O3 -shared ~/test.c -o test.so 
```
    
