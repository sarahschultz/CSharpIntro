C# Training
LinkedIn Learning Getting Started as a C# Developer

https://www.linkedin.com/learning/paths/getting-started-as-a-c-sharp-developer

1. C# Essential Training Types and Control Flow
Matt Milner, January 2022
2 hours 38 minutes


Context in which the program executes
C# code file compiles to MSIL - Microsoft Intermediate Language
(F# and vb.NET also are compiled to MSIL)

Once compiled to MSIL, they need to be executed.
.NET runtime executes the intermediate language.

Basic Structure of C# Program:
Namespaces --> Class --> Members --> Blocks --> Statements


Example of interesting syntax:

Switch Statement
(If-else would be too cumbersome to read and/or write)
Syntax:
Switch (expression whose value you want to test) {
Individual case statements for which to evaluate, with break statements
}

We can also define a default label which is like a catch-all "else statement"
If you have 4 or more if statements, use switch cases.

In general, use only 2-3 if else statements, otherwise use the switch cases.

For loops look the same as in javascript 
Make sure you keep track of the initialization path, and then the loop condition.
Incrementing i is the same as in JS as well, by i++ or i--

For each in - iterating over sequences of values

Using the WHILE keyword syntax:
While (logical expression) {
Do the following thing(s)
}

There’s also a DO WHILE loop, but it looks different.


do {

} while (logical expression);

Outputs may be the same but the do while loop will AT LEAST run once because the condition check is done at the bottom of the loop, where in while it’s checked first.


Exceptions
Exception handling to help catch errors before they hit the user i.e. our try/catch block

String Operations
Append Functions


Look at the String Builder Class or Microsoft documentation:

https://lkd.in/gspyQD5


Parse the Contents of a String into Native C# Data Types

Parse Strings in the Microsoft docs at Microsoft .NET information documentation

Applying a default value or with a value in a function and won’t throw errors

Can also call functions using the name of the parameters

Reference and Out Parameters
Use the ref keyword, indicates to the compiler that the argument is passed as a reference rather than a copy so it can change without being outside of the function.

The out keyword specifies that a parameter is used to return a value instead of supplying data to the function
the parameters are going to be used to return values back to the caller, and not used to supply data TO the function

When you call the function, you need the out keywords in the arguments