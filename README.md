# rustcc

A Tiny C Compiler written in Rust

Based on Writing a C Compiler by Nora Sandler

Usage:

cargo run rustcc <input_file.c>

For running each stage separately use the following flags
options:
```  
-h, --help      Display a help message
-l, --lex       Print token after lexical analysis
-p, --parse     Parse the input file and display the AST
-cg, --codegen  Print generated assembly code
--all           Enable all output phases
  ```

## References:

[Nora Sandler's Blog](https://norasandler.com/2017/11/29/Write-a-Compiler.html): A blog post that explains parts of the compiler in detail.
[Lox](https://github.com/Meillaya/Lox): An AST interpreter I built in Rust.
