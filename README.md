# Stacks, Queues - LIFO, FIFO

### Description

The monty, a language intended to be equally suitable for both scripting and conventional programming.
Monty features an unusually flexible type system in which all values
are viewed as objects in a single-inheritance class hierarchy,
static and dynamic typing are smoothly integrated.

### Usage

- Includes monty.h
- The file argument must have a .m extension.
- Included in the file should be the instructions for the byte code interpreter:
```
user:~/monty$ cat -e bytecodes/000.m
push 0$
push 1$
push 2$
push 3$
pall    $
push 4$
push 5    $
      push    6        $
pall$
```

### OpCodes

OpCode | Description
--- | ---
push <int> | pushes an element to the stack
pall | prints all the values on the stack, starting from the top of the stack
'pint' | prints the value at the top of the stack, followed by a new line
'pop' | removes the top element of the stacks
'swap' | swaps the top two elements of the stacks
'add' | adds the top two elements of the stack
'nop' | doesn’t do anything
'sub' | subtracts the top element of the stack from the second top element of the stack
'div' | divides the second top element of the stack by the top element of the stack
'mul' | multiplies the second top element of the stack with the top element of the stacks
'mod' | computes the rest of the division of the second top element of the stack by the top element of the stack

### About

This project was created by Ahmed Zghal & Ali Dehissy

