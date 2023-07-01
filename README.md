# Compiler Design Experiment at Nanjing University
## Overall Objective
The principal aim of this series of experiments is to design and implement a compiler for the C-- programming language.

## Lab 1: Lexical and Syntax Analysis
In the first laboratory experiment, we utilize the flex lexical analyzer generator and the Bison parser generator to perform lexical and syntax analysis respectively. Flex will facilitate the tokenization of the source code, and Bison will transform these tokens into a syntax tree based on the predefined grammar rules of the C-- language.

## Lab 2: Semantic Analysis
Building upon the syntax tree produced in Lab 1, this stage involves semantic analysis to check for semantic consistency within the source code. Any detected semantic errors will be appropriately reported. This phase also entails constructing a symbol table which will be used to keep track of identifier declarations and their attributes.

## Lab 3: Intermediate Code Generation
This lab exercise extends the lexical, syntax, and semantic analyzer by translating the C-- source code into an intermediate representation. The chosen format for this stage is three-address code, which balances readability with efficiency, simplifying subsequent optimization steps and target code generation.

## Lab 4: Target Code Generation
The culmination of this series of experiments is the generation of target code. Using the results of the lexical analysis, syntax analysis, semantic analysis, and intermediate code generation, the source code in C-- will be translated into a sequence of MIPS32 instructions. This step ultimately allows the C-- source code to be executed on a machine or emulator supporting the MIPS32 instruction set architecture.

The entire journey, from high-level C-- code to machine-level MIPS32 instructions, presents an in-depth, hands-on exploration of the workings of a compiler, allowing participants to appreciate the complex and fascinating process behind program execution.
