# Week 2 - Arrays

Tags: C
Date: October 22, 2023

- Content
    
    Preprocessing. Compiling. Assembling. Linking. Debugging. Arrays. Strings. Command-Line Arguments. Cryptography.
    

[lecture2.pdf](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/lecture2.pdf)

# Notes

[Lecture 2 - CS50x 2023](https://cs50.harvard.edu/x/2023/notes/2/)

# Content

- compiling
    - preprocessing
        
        “Read” the other archives needed in the file, creating a function **prototype** of the included archives on the top.
        
        ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled.png)
        
    - compiling
        
        ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%201.png)
        
    - assembling
        
        ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%202.png)
        
    - linking
        
        ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%203.png)
        
        ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%204.png)
        
- debugger
    
    debug50 to use the cs50 debugger.
    
    ```html
    debug50 ./program
    ```
    
    printf() is a good tool for little bugs.
    
- Arrays
    
    Inside the computer, this is how the arrays are stored:
    
    ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%205.png)
    
    ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%206.png)
    
    - The value in a array are passed by reference.
        
        The callee receives the actual array, not a copy of it, like the variables in functions calls.
        
- Strings
    
    A string is a array of Chars.
    
    Nul is the 00000000 byte in the encoding pattern and defines the end of a String.
    
    ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%207.png)
    
    A array can store words, and the words are Strings that’s arrays of Chars.
    
    ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%208.png)
    
    ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%209.png)
    
- String length
    
    You can use a standard library of C called string.h, to use the **strlen()** function and get the string length.
    
    ```html
    #include <string.h>
    
    string name = "Lucas";
    int length = strlen(name);
    printf ("%i\n", length);
    
    Output: 5
    ```
    
    You can also use a function to uppercase the string in C, importing the ctype.h in the top of the code:
    
    ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%2010.png)
    
- command-line arguments
    
    ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%2011.png)
    
- Exit status
    
    ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%2012.png)
    
- Encryption
    
    ![Untitled](Week%202%20-%20Arrays%20fc147817be1e4448b4af057f3c984e60/Untitled%2013.png)
