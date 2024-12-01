# Timeline

## 2024/10/21
- Start following along with the textbook.
- Set up Go on machine.

## 2024/10/22
- Ch 1.1-1.2
- Create token.go

## 2024/10/23
- Ch 1.3-1.5
- Create our tokenizer and extended it to the full Monkey token list
- Start creating our REPL (without the E)

## 2024/10/27
- Ch 2.1-2.4
- What is a parser. We will create a "recursive descent parser", in particular a "top down operator precedence" parser (or a Pratt Parser).
- Parse let statements (without the expression)
- Print out list of errors in test suite

## 2024/11/06
- Ch 2.5-2.7
- Parse return statements (without the expression)
- Parse expressions using Pratt Parsing
    - Implement order of operations (without grouping)

## 2024/11/09
- Ch 2.8-2.9
- Finish the parser
    - Parse booleans, grouped expressions, if expressions, functions, and function calls.

## 2024/11/10
- Ch 3.1-3.6
- Learn about evaluation strategies (tree-walk, convert to bytecode, JIT)
- Create objects that wrap simple types
- Evaluate integer and boolean expressions
- Add conditional expressions

## 2024/11/21
- Ch 3.7-3.10
- Return values (and dealing with nested blocks of statements)
- Report errors
- Set up an environment to support let statements and variables
- Support functions and functino calls

## 2024/11/22
- Ch 3.11, Ch 4.1-4.2
- Accept that implementing a garbage collection system in GO is out of scope, and reuse GO's garbage collector.
- Add strings and support concatenation

## 2024/11/30
- Ch 4.3-4.6
- Create support for built-in functions (and implement len, first, last, rest, push)
- Add arrays and hash tables
- Add printing to the console (via the built-in function puts())
- Officially finish following along to *Writing an Interpreter in Go* by Thorsten Ball