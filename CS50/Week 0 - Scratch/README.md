# Week 0 - Scratch

- Content
    
    Computer Science. Computational Thinking. Problem Solving: Inputs, Outputs. Representation: Unary, Binary, Decimal, ASCII, Unicode, RGB. Abstraction. Algorithms. Running Times. Pseudocode. Scratch: Functions, Arguments, Return Values; Variables; Boolean Expressions, Conditionals; Loops; Events; Threads.
    

### Key Concepts:

- Binary
    - Bit is the abbreviation of Binary digiT.
    - The binary system uses the power of two.
        
        In the binary system, each bit represents an increasing power of 2, with the rightmost bit representing 2 to 0, the next representing 2 to 1, then 2 to 2, and so on.
        ![binary](https://github.com/LucasSch2410/OSSU/assets/45702317/8307d66a-f572-44f5-90db-19184d2d954f)        
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
    ![algorithm](https://github.com/LucasSch2410/OSSU/assets/45702317/7ada8576-fe93-4f79-9439-73e2d6015e72)
    
    - Implementation details about large data.
        
        It’s faster to use a logarithm that cuts the data in the middle and searches if the data in specific is more to the right or more to the left and cuts again and again.
        
        If you search item per item(n), or two items(n/2) it will consume more time.
      
        ![logarithm](https://github.com/LucasSch2410/OSSU/assets/45702317/39e5a719-6132-4c9f-b9b2-0c7b0c0e83b7)
        
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
