![UPY logo](https://static.wixstatic.com/media/e16f80_9c4ca79ed84340e0984c64712e35448c~mv2_d_3000_2100_s_2.png/v1/fill/w_370,h_138,al_c,q_85,usm_0.66_1.00_0.01/e16f80_9c4ca79ed84340e0984c64712e35448c~mv2_d_3000_2100_s_2.webp)

## Students: 

[Diana Rivero](https://github.com/20DianaRivero01/Programming2/blob/master/introstructureprogramming.md)
[David Romero](https://github.com/David2903/programming2)
_
# CLASSIFICATION OF PROGRAMMING PARADIGMS #

## PROGRAMMING PARADIGMS ##
A **Paradigm**is a style, or “way,” of programming and is used as a method to solve some problems or do some task. Normally the way of solve the problems are by using a programming language and as we know, there are lots of programming language that are known, but all of them need to follow some strategy when they are implemented and this methodology/strategy is paradigms.(the instructions).

Apart from varieties of programming language paradigms has their classification to fulfil each and every demand. There are two types of paradigms:

### DECLARATIVE
**Declarative languages**, also called nonprocedural or very high level, are programming languages in which (ideally) a program specifies what is to be done rather than how to do it.

#### Clasification
 
#### Functional 
According to GeeksforGeeks, *Functional programming* is a programming paradigm where we have a style of building the structure and elements of computer programs. Here we treat computation as an evaluation of mathematical functions and you avoid changing-state and mutable data. Basically a better way to understand this is asking it as “what to solve”. Also we use expressions instead of statements so in this case the expression is evaluated to produce a value whereas a statetment is executed to assing variables. 
#### Data-flow 
It is a paradigm that represents applications as a direct graph, similar as a dataflow diagram. Those applications are represented as a set of nodes or also called “blocks” with an input and/or output ports in them. The nodes can be sources, sinks or processing blocks to the information flowing in the system, like a processes communicating with each other over predefined channels; it means that nodes are connected by direct edges thar define the flow of information between them. 
#### Logic 
Then we have a kind of imperative programming where control flow is defined by nested loops, conditionals, and subroutines and it is called *Logic Programming paradigm*. In this system, the main emphasize is on knowledge base and the problem, thats why, the execution of the program is very much like proof of mathematical statement.
#### Structure 
It is also known as modular programming. It facilitates the creation of programs with readable code and reusable components. All modern programming languages support structured programming, but the mechanisms of support, like the syntax of the programming languages, varies.
This paradigm encourages dividing an application program into a hierarchy of modules or autonomous elements, which may, in turn, contain other such elements. Within each element, code may be further structured using blocks of related logic designed to improve readability and maintainability.
#### Template-base programming
This paradigm is basically based on solving a problem dividing it into smaller problems. It works dividing into simpler problems, the aim is to obtain an easier solution.
### Imperative 
Is a paradigm of computer programming in which the program describes a sequence of steps that change the state of the computer, it means that it explicitly tells the computer "how" to accomplish. The steps.
#### Von Neumann
It is a high-level language, is an architecture based on the stored-program computer concept, where instruction data and program data are stored in the same memory, it is conformed of a single, shared memory for programs and data, a single bus for memory access, an arithmetic unit, and a program control unit. The Von Neumann processor operates fetching and execution cycles seriously, and his computer architecture design consists of a Control Unit, Arithmetic and Logic Unit (ALU), Memory Unit, Registers and Inputs/Outputs.
#### Script
Another helping language is the *Scripting language*, which is basically a language where instructions are written for a run time environment. They do not require the compilation step and are rather interpreted. It brings new functions to applications and glue complex system together. A scripting language is a programming language designed for integrating and communicating with other programming languages such as: bash, Node js, Ruby, Python and Perl. The main characteristics of this language is that it is easy to learn, fast editing, interactive and functionality.
#### Object-Oriented Programming (OOP). 
According to Tech-target, the OPP is a computer programming model that organizes software design around data, or objects, rather than functions and logic. An object can be defined as a data field that has unique attributes and behavior. It is focus on the objects that developers want to manipulate rather than the logic required to manipulate them. This approach to programming is well-suited for programs that are large, complex and actively updated or maintained.
## Methods of Programming Paradigms ##

#### Interpreted Programming:
This method doesn’t need to be preprocessed by a compiler, that is, it executes the sequence of instructions without the need to read and translate everything.
#### Compiled programming:
It is a programming language whose implementations are normally compilers (translators that generate machine code from the source code). The keyword that describes a compiled pogramming is the compiled do like a step else (first you write te code and after that code is translated to bytecode and after a language that the machine can understand.
#### Source Code
It is a set of lines of text with the steps the computer must follow to run a program. Is wrote in a programming language but is not ready to execute, it needs to be translated by a compiler

# DATA REPRESENTATIONS AND OPERATORS #
_
#### Identifiers
Identifiers are names for entities in a C program, such as variables, arrays, functions, structures, unions and labels. An identifier can be composed only of uppercase, lowercase letters, underscore and digits, but should start only with an alphabet or an underscore. If the identifier is not used in an external link process, then it is called as internal. Example: Local variable. If the identifier is used in an external link process, then it is called as external. Example: Global variable
#### Variable
In programming, a variable is a value that can change, depending on conditions or on information passed to the program. Typically, a program consists of instruction s that tell the computer what to do and data that the program uses when it is running.
#### Constants
Data values that stay the same every time a program is executed are known as constants. Constants are not expected to change.
#### Reserved word
Often found in programming languages and macros, reserved words are terms or phrases appropriated for special use that may not be utilized in the creation of variable names. For example, "print" is a reserved word because it is a function in many languages to show text on the screen.
#### Primitive data type
In simple terms “data type” and “primitive data type” are simply known and used as interchangeable variables. Primitive data types are predefined types of data, which are supported by the programming language. For example, integer, character, and string are all primitive data types.
**Memory space and range of values**
* Integer: Keyword used for integer data types is int. Integers typically requires 4 bytes of memory space and ranges from -2147483648 to 2147483647.
* Character: Character data type is used for storing characters. Keyword used for character data type is char. Characters typically requires 1 byte of memory space and ranges from -128 to 127 or 0 to 255.
* Boolean: Boolean data type is used for storing boolean or logical values. A boolean variable can store either true or false. Keyword used for boolean data type is bool.
* Floating Point: Floating Point data type is used for storing single precision floating point values or decimal values. Keyword used for floating point data type is float. Float variables typically requires 4 byte of memory space.
* Double Floating Point: Double Floating Point data type is used for storing double precision floating point values or decimal values. Keyword used for double floating point data type is double. Double variables typically requires 8 byte of memory space.
* Void: Void means without any value. void datatype represents a valueless entity. Void data type is used for those function which does not returns a value.
* Wide Character: Wide character data type is also a character data type but this data type has size greater than the normal 8-bit datatype. Represented by wchar_t. It is generally 2 or 4 bytes long.
* C: Composite Types: Composite data types are user defined data types that consist of several elements grouped together. Usually data elements are stored close together in consecutive memory addresses.
*There are several composite data types in C.*
* Arrays
* Strings
* Structures
* Unions	
Basic fuctions of input/output (I/O)
* scanf reads formatted input from stdin.
* printf sends formatted output to stdout.
* getcharand putchar are used to transfer single characters.
* puts is used to output strings.
## REFERENCES ##
https://www.geeksforgeeks.org/introduction-of-programming-paradigms/
https://www.geeksforgeeks.org/functional-programming-paradigm/
https://www.researchgate.net/publication/281777036_Dataflow_Programming_Concept_Languages_and_Applications  
https://www.geeksforgeeks.org/introduction-of-programming-paradigms/
https://searchsoftwarequality.techtarget.com/definition/structured-programming-modular-programming
https://www.computerhope.com/jargon/i/imp-programming.htm 
https://www.computerscience.gcse.guru/theory/von-neumann-architecture
https://www.geeksforgeeks.org/introduction-to-scripting-languages/
https://searchapparchitecture.techtarget.com/definition/object-oriented-programming-OOP 
http://aboutc.weebly.com/identifiers.html 
https://sagecode.net/c-composite-types/ 
https://dl.sumdu.edu.ua/textbooks/103395/597162/index.html 
https://tutsmaster.org/difference-between-primitive-and-non-primitive-data-types-2/ 
https://www.computerhope.com/jargon/r/reseword.htm
