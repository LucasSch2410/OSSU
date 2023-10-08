# Week 0 - Scratch

- Content
    
    Computer Science. Computational Thinking. Problem Solving: Inputs, Outputs. Representation: Unary, Binary, Decimal, ASCII, Unicode, RGB. Abstraction. Algorithms. Running Times. Pseudocode. Scratch: Functions, Arguments, Return Values; Variables; Boolean Expressions, Conditionals; Loops; Events; Threads.
    

[lecture0.pdf](https://prod-files-secure.s3.us-west-2.amazonaws.com/7951f31a-9e83-4a4e-ba8c-d848f0871260/9192a86c-a3a9-4e94-9181-7aed663c9d40/lecture0.pdf)

### Key Concepts:

- Binary
    - Bit is the abbreviation of Binary digiT.
    - The binary system uses the power of two.
        
        In the binary system, each bit represents an increasing power of 2, with the rightmost bit representing 2 to 0, the next representing 2 to 1, then 2 to 2, and so on.
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/7951f31a-9e83-4a4e-ba8c-d848f0871260/f7dbbd20-53e3-4efb-bd81-95018d9e9c3b/Untitled.png)
        
- Representation
    - ASCII
        
        ASCII represents characters between 32 and 127, codes below 32 are called unprintable and are used just for control. Use 7 bits, but have a bit to spare, are used in an 8-bit system.
        
    - Unicode
        
        The Unicode brought a pattern, with a standard that is used today with almost all modern languages (or old languages too).
        
        Unicode has a ***code point***, a number that assigns every character, like **U+0639**.
        
        - Encoding
            - UTF-8
            - UTF-16
            - UTF-32
            - UCS-2
    - RGB
        
        Each dot-pixel has three bytes.
        
        - Red - 256
        - Green - 256
        - Blue - 256
- Algorithms
    
    It’s a step-by-step instructions for solving some problems, between the input and output.
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/7951f31a-9e83-4a4e-ba8c-d848f0871260/3ec2cd37-a426-4eb2-bc9f-7b4aa09909b9/Untitled.png)
    
    - Implementation details about large data.
        
        It’s faster to use a logarithm that cuts the data in the middle and searches if the data in specific is more to the right or more to the left and cuts again and again.
        
        If you search item per item(n), or two items(n/2) it will consume more time.
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/7951f31a-9e83-4a4e-ba8c-d848f0871260/a9665521-5722-4118-bf55-8413f5956133/Untitled.png)
        
- Abstraction
    
    Don’t focus on the low-level implementation details making a simplification of this thing. Then looking at the essential problems and dealing with smaller and smaller problems.
    
    - Pseudocode abstraction
        - functions
        - conditionals
        - Boolean expressions
        - loops
        - variables
        - …
        
- Custom blocks, functions
    
    Functions are abstractions that let you implement algorithms, and you don’t have to care or remember how the function was built, just call her.