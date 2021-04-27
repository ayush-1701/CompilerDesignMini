# CompilerDesignMini
Mini Project of Compiler Design

Implementation of compiler for C++, following needs to be implemented:
a.	Design and Implementation of Lexical analyzer for C++
b.	Design and Implementation of Syntax analyzer for C++
c.  Code Generation of basic functionality


To Run the code: 
gcc Code/Lexical.c -o lex
gcc Code/Syntax.c -o syntax
gcc Code/CodeGen.c -o codegen

//For LEXICAL ANALYZER
./lex testcase1.txt > lexout.txt
cat lexout.txt

//For SYNTAX ANALYZER
./syntax lexout.txt > synout.txt
cat synout.txt

//For CODE GENERATION
./codegen synout.txt > machinecode.txt
cat machinecode.txt
