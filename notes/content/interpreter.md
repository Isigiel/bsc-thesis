# Interpreters

## Structure

- Basics
- Advantages
- WASM3

## Text

### Interpreters|Basics

Interpreters are computer programs that execute a program. They pose a different concept to compiled execution, where a program would be translated to machin code before being run directly on the CPU. While offering multiple advantages the main drawback is the execution speed compared to native code execution which is often slower by an order of magnitude and sometimes more. The oberhead is generated byt the interpreter having to analyze the program code before it can be executed.

### Interpreters|Advantages

Interpretes thus offer benefits in development speed since the code does not have to be recompiled to run and in portability because the same code could be run on multiple platform specific interpreters without the need to compile it into the native machine code of multiple platforms. For our usecase the interpreter executes WASM instructions, allowing the dynamic loading of modules and running them in the chose environment.