[back](README.md)

# Concepts

## Stack vs. Heap Variables

**Stack Variables** - Declared in a function and automatically freed when the function returns.

**Heap Variables** - Dynamic, manually handled memory allocation. Can exist beyond the scope of a function. Helpful when the size of the data is unknown at compile time. Can use `malloc`, `calloc`, or `realloc` to allocate.

## A Pointer to a Pointer

If you pass a single pointer to a function, the function can modify the data it points to, but it cannot change where the pointer points (because C passes arguments by value).

