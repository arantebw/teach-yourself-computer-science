# Cloud Computing

## Azure Development

### Certified Entry-Level Python Programmer Certification

#### Chapter 1: Getting Started

##### Course Introduction

##### About the Training Architect

#### Chapter 2: Environment Setup

##### Picking a text editor or IDE

##### Installing Python 3.7 on a Cloud Playground Server

#### Chapter 3: Fundamental Concepts

##### Compilers and Interpreters

##### Lexing, Syntax, and Semantics

Lexing (lexical analysis) is a process of converting the code into unique
sequence of tokens, using a lexer (lexical analyzer).

Parsing (syntax analysis) is a process of checking the grammar of your code by
going through the sequence of tokens if it follows the rules of the language,
using parser (syntax analyzer). If nothing went wrong it will create an AST
(abstract syntax tree), otherwise it will return a syntax error.

Semantic analysis is the process of checking the logical correctness of the
generated AST by the parser, if nothing went wrong the AST is then passed
to the compiler/interpreter, otherwise it will return a semantic error.

##### Python Specifics: Keywords and Instructions

##### Using the REPL

##### Creating a Python file

#### Chapter 4: Literals, Variables, and Comments

##### Comments

Use `#` to comment a line or a statement.

Python has no syntax for a block comment.

`"""` is not a block comment, it is used to create a multi-line string, and
treated as an object, so a memory is allocated for it.

##### Variables and Assignment Operators
