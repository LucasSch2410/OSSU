# Week 1 - C

- Content
    
    C. Source Code. Machine Code. Compiler. Correctness, Design, Style. Visual Studio Code. Syntax Highlighting. Escape Sequences. Header Files. Libraries. Manual Pages. Types. Conditionals. Variables. Loops. Linux. Graphical User Interface (GUI). Command-Line Interface (CLI). Constants. Comments. Pseudocode. Operators. Integer Overflow. Floating-Point Imprecision.
    

## Manual Pages - Documentation

[CS50 Manual Pages](https://manual.cs50.io/)

## Notes

https://cs50.harvard.edu/x/2023/notes/1/

## Content 

- Compiler
    
    The compiler transforms de source code into the machine code, that works with de binary system.
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/7951f31a-9e83-4a4e-ba8c-d848f0871260/827e4b6a-ab91-4720-98b1-c4623f622ae1/Untitled.png)
    
- Correctness, design, style - Principles
    - Correctness - does the code run as intended?
    - Design - how well is the code designed?
    - Style - how aesthetically pleasing and consistent is the code?
- Escape sequences
    - \n in C code to create a new line.
- Libraries
    
    ### Standard I/O Library
    
    ```c
    #include <stdio.h>
    ```
    
    - It’s a header file that Includes the basic library in the first line of Input and Output called **Standard I/O Library.**
- Format codes
    - ‘%s’ is a placeholder for a string in the printf function.
        
        ```c
        printf("hello, %s\n", name);
        ```
        
    - ‘%i’ is a placeholder for an integer in the printf function.
    - ‘%li’ is a placeholder for a long integer.
    - ‘%f’ is a placeholder for floating-point values with decimals.
    - ‘%c’ is a placeholder for a character.
- Data Types
    - char
    - bool
    - int - 32 bits
    - long - 64 bits longer integer
    - string
    - float - 32 bits
    - double - 64 bits longer floats
- Conditionals
    
    Single characters have to be within single quotes, and strings of text need to be within double quotes.
    
    - If
        
        The if statement can have a Boolean output (condition) with the || operator.
        
        ```c
        char c = get_char("Do you agree? ");
        
        if (c == 'y' || c == 'Y')
        {
        	printf("Agreed.");
        }
        else if (c == 'n' || c == 'N')
        {
        	printf("Not agreed.");
        }
        ```
        
- Loops and variables
    - while
        
        ```c
        int i = 0
        
        while(i < 3)
        {
        	printf("Meow");
        	i++;
        }
        ```
        
    - for
        
        ```c
        for (int i = 0; i < 3; i++)
        {
        	print("Meow");
        }
        ```
        
    - do while
        
        This code always will run one time, and will run more times if the while condition is true.
        
        ```c
        int n;
        do
        {
        	n = get_int("Size: ");
        }
        while (n < 1);
        ```
        
- CLI
    - Command Line Interface
    - Linux
    - Commands
        - ls - List all of the files in the folder.
        - mv - move or rename the file
        - cd - enter into folders
        - cp - copy a file
        - mkdir - make a directory
        - rm - remove a file
        - rmdir - remove a directory
- void
    - the keyword void can be used to define a function that doesn’t have a return value (only has side effects) or a parameter in an argument of a function.
- integer overflow
    
    Useful link: https://www3.ntu.edu.sg/home/ehchua/programming/java/DataRepresentation.html
    
    It’s where you want to use more bits than you have available. The biggest positive number with 32 bits that can be represented is 2147483647. More numbers will overflow because are going to run out of bits and return to the initial binary value. For example when a computer with 3 bits tries to run the number 8 in binary:
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/7951f31a-9e83-4a4e-ba8c-d848f0871260/e7294ce2-76cf-4367-80d5-4c9ee9ee9d75/Untitled.png)
    
    - truncation and type casting
        
        It’s when you truncate the decimals of a floating-point value. It’s necessary to explicitly convert the value into a float format. (**type casting**):
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/7951f31a-9e83-4a4e-ba8c-d848f0871260/f66724a9-5257-4d05-ad51-413b7227e4a2/Untitled.png)
        
    - floating-point imprecision
        
        If you have only a finite of bits, so have a finite limit of precision. With the **float**, you have 32 bits, but with the **double**, you will have the double of bits for more precision with 64 bits.
