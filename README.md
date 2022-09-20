# About The Project

## An interpreter for a subset of the Scheme language.
Robustness, light weight, easy to use, support most of scheme's features and functionalities.

Implemented a scheme intepreter by python, support scheme language' features like lambda, define function in current frame, bind variables in frame arithmic and logic operations, quote, begin make new frame, conditional branch, do mu form)

The main implementation is done by using read-evaluate-apply loop, parsing user's input string into a linked list data structure , passing the linked list ds to different functions to implementing scheme's special forms.

Using high order function, recurrision, tail recurrision and data structures like tree and linked list to optimize the performance of codes.



## Using UCB cs61a fall 2020's project4 as skeleton and inspiration.
Pass the autotester of Berkley's autograde test framework, gain a descent grade.


## Scheme features

1. Read-Eval-Print

    Read: Parsing user input(a String of Scheme code)

    Eval: This step evaluates Scheme expressions (represented in Python) to obtain values. 

    Print: This step prints the __str__ representation of the obtained value.


2. Load

    The interpreter can evaluate the expression in an input file by passing the file name as a command-line argument.

3. Symbols

    The interpreter is case-insensitive.

4. Turtle Graphics
   
    Including procedure calls to the Python turtle package.

## Running the interpreter

To start an interactive session:

    pyhton3 scheme.py


To evaluate the expressions in an input file by passing the file name as a command-line argument to scheme.py:

    python3 scheme.py fileName.scm
    

To exit the Scheme interpreter:

    scm> (exit)

## Contributing
UCB's cs61a team and Kechen Liu


## Contact
Auther: Kechen Liu 

Email: kechenkristin@gmail.com

Project Link: https://github.com/kechenkristin/Scheme
