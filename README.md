# Stack
## General information

This is a library that introduces a new data structure into the C programming language: the STACK.

Stack is a data structure organized according to the "last-in, first-out" principle.

## Documentation

**Note:** ELEM stands for any numeric data type, which is typically an integer by default. If you want to change this, you can go to the "stack.h" file and change the definitions of "ELEM" and "SPEC" from an integer to any other data type

+ ` void StackConstructor(STACK *st, const size_t length)` - Initializing a stack **st** of length **length**.
+ `void StackPush(STACK* st, ELEM value)` - adding an item **elem** to the stack **st**.
+ `void StackDestructor(STACK* st)` - deleting the stack **st** clearing the occupied memory
+ `ELEM StackPop(STACK* st)` - Removing the last element from the stack and returning it
+ `void PrintStack(STACK* st)` - Printing all stack items to the console.

## Example

An example of the code can be found in the main.c file.

## Program start

```C
>>>gcc main.c
>>>./a.exe
```
