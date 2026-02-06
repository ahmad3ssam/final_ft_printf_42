# final_ft_printf_42


## Description

`ft_printf` is a custom implementation of the standard C `printf` function.  
The goal of this project is to reproduce the behavior of `printf` using only allowed C functions and handling different format specifiers.  

This project helps to:

- Understand variadic functions (`stdarg.h`)
- Work with formatted output
- Manage strings, numbers, and characters efficiently
- Handle edge cases like `%s` with `NULL`, `%d` negatives, and `%p` pointers
- Build a reusable and robust printing function for future C projects
---

## Project Structure

ft_printf/

├── print/

│         ├── ft_*.c

│         └── ft_printf.h

├── ft_printf.c

├── main.c

├── Makefile

└── README.md

---
## Instructions

### Compilation

To compile the library:

```bash
make
```
This will generate:

```bash
libftprintf.a and *.o files
```

After creating main.c, compile it with the library:

```bash
cc main.c libftprintf.a
```
### Addition Rules
```bash
make clean     # Remove object files
make fclean    # Remove object files and libft.a
make re        # Recompile the library
```
