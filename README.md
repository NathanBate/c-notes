# C Notes

Various notes about the C programming language. Not necessarily a tutorial, but helpful like one.

A helful reference website for C can be found at
[https://en.cppreference.com/w/c](https://en.cppreference.com/w/c.com).

# Stack vs. Heap Variables

**Stack Variables** - Declared in a function and automatically freed when the function returns.

**Heap Variables** - Dynamic, manually handled memory allocation. Can exist beyond the scope of a function. Helpful when the size of the data is unknown at compile time. Can use `malloc`, `calloc`, or `realloc` to allocate.