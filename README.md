# printf

A custom implementation of the `ft_printf` function.

This 42 project is about handling variable arguments, formatted output, and writing modular C code.

## What’s in it
- Supports `%c`, `%s`, `%d`, `%i`, `%u`, `%x`, `%X`, `%p`, and `%%`
- Handles width, precision, and flags
- Returns the number of characters printed

## How to use
A Makefile is included. Simply run:
```bash
make
```

This will compile all .c files and create libftprintf.a.
Include ft_printf.h and link with the library in projects.

## Example:

```
#include "ft_printf.h"

int main(void)
{
    ft_printf("Hello %s, number: %d\n", "world", 42);
    return (0);
}
```
---

## Note

This code is for educational purposes only and should not be copied for assignments or projects elsewhere.
