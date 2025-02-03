# REPL
REPL stands for "read-eval-print loop". It's a common type of program that allows for interactivity. You type in a command, and the program evaluates it and prints the result. You can then type in another command, and so on.

Your native terminal's command line is a REPL! Our Pokedex will also be a REPL. In this step, we're just going to build the bones of the REPL: a loop that parses and cleans an input and prints the first word back to the user. Here is what your program should be able to do after this step:

```shell
> go run .
Pokedex > help me
help
Pokedex > Exit
exit
Pokedex > WHAT even is a pokeman?
what
```

## Running and logging

Run the application and tee to log file
```shell
go run . | tee repl.log
```
