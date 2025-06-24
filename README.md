# C-Compiler
C-Compiler based on specification in "Writing a C Compiler" by Nora Sandler

Monorepo with the compiler being implemented in multiple languages (or at least an attempt):
* C
* C++ (tentative)
* Rust
* Python

## Building
Build all the compilers for each language with the `build.sh` script. The language can also be specified via the `--language` flag.

## Running
Run any one of the compilers with the following command:
```
```

## Running tests
All tests are provided by a third-party, found [here](https://github.com/nlsandler/writing-a-c-compiler-tests).
For all languages all tests are run with the script `runTests.sh`. Language can be specified with the `--language` flag. Lexing and parsing method can be specified with the `--lexer` and `--parser` flags respectively.
