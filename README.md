# Refactorex for VS Code

Uses the [Refactorex](https://github.com/gp-pereira/refactorex) language server to 
enhance VS Code with code actions to quickly refactor Elixir. 

![Example](https://github.com/gp-pereira/refactorex-vscode/blob/main/assets/readme.gif?raw=true)

## Available refactorings
* __Function__
  * [x] [Expand anonymous function](#function-expand-anonymous-function) 
  * [x] [Extract anonymous function](#function-extract-anonymous-function) 
  * [x] [Extract function](#function-extract-function) 
  * [ ] Inline function
  * [ ] Rename function
  * [x] [Underscore unused args](#function-underscore-unused-args) 
  * [x] [Use keyword syntax](#function-use-keyword-syntax) 
  * [x] [Use regular syntax](#function-use-regular-syntax) 

* __Pipeline__
  * [x] [Pipe first arg](#pipeline-pipe-first-arg) 
  * [x] [Remove pipe](#pipeline-remove-pipe) 

* __Variable__
  * [x] [Extract constant](#variable-extract-constant)
  * [ ] Extract variable
  * [ ] Inline constant
  * [ ] Inline variable
  * [ ] Rename constant
  * [ ] Rename variable
  * [ ] Underscore long number

## How to use each refactoring

### Function: expand anonymous function

* __Description__: expand an anonymous function from & to fn -> end syntax
* __Works on__: anonymous function selection

![Example](https://github.com/gp-pereira/refactorex-vscode/blob/main/assets/examples/function/expand_anonymous_function.gif?raw=true)

[▲ top](#available-refactorings)

<br>

### Function: extract anonymous function

* __Description__: extract the anonymous function into a private function
* __Works on__: anonymous function selection

![Example](https://github.com/gp-pereira/refactorex-vscode/blob/main/assets/examples/function/extract_anonymous_function.gif?raw=true)


[▲ top](#available-refactorings)

<br>

### Function: extract function

* __Description__: extract the selection into a private function
* __Works on__: selection

![Example](https://github.com/gp-pereira/refactorex-vscode/blob/main/assets/examples/function/extract_function.gif?raw=true)

[▲ top](#available-refactorings)

<br>

### Function: underscore unused args

* __Description__: places an underscore in front of function args not used.
* __Works on__: function definition line or function clause line

![Example](https://github.com/gp-pereira/refactorex-vscode/blob/main/assets/examples/function/underscore_unused_args.gif?raw=true)

[▲ top](#available-refactorings)

<br>

### Function: use keyword syntax

* __Description__: rewrite the regular function (do end) using keyword syntax (, do:)
* __Works on__: function definition line

![Example](https://github.com/gp-pereira/refactorex-vscode/blob/main/assets/examples/function/use_keyword_syntax.gif?raw=true)

[▲ top](#available-refactorings)

<br>

### Function: use regular syntax

* __Description__: rewrite the keyword function (, do:) using regular syntax (do end)
* __Works on__: function definition line

![Example](https://github.com/gp-pereira/refactorex-vscode/blob/main/assets/examples/function/use_regular_syntax.gif?raw=true)

[▲ top](#available-refactorings)

<br>

### Pipeline: pipe first arg

* __Description__: pipe the first arg into call
* __Works on__: line

![Example](https://github.com/gp-pereira/refactorex-vscode/blob/main/assets/examples/pipeline/pipe_first_arg.gif?raw=true)

[▲ top](#available-refactorings)

<br>

### Pipeline: remove pipe

* __Description__: remove the pipe operator and put first arg inside call
* __Works on__: pipe line

![Example](https://github.com/gp-pereira/refactorex-vscode/blob/main/assets/examples/pipeline/remove_pipe.gif?raw=true)

[▲ top](#available-refactorings)

<br>

### Variable: extract constant

* __Description__: extract the selection into a module constant
* __Works on__: selection

![Example](https://github.com/gp-pereira/refactorex-vscode/blob/main/assets/examples/variable/extract_constant.gif?raw=true)

[▲ top](#available-refactorings)

<br>
