# 🖨️ ft_printf

A custom implementation of the printf function, created as part of the 42 curriculum.

## 🔍 About

ft_printf is a recreation of the standard C library printf function, handling various format specifiers and conversion rules. This project teaches variadic functions, string parsing, and structured programming.

## ✨ Features

### Format Specifiers
- `%c` - Single character
- `%s` - String
- `%p` - Pointer address
- `%d` - Decimal (base 10) integer
- `%i` - Integer in base 10
- `%u` - Unsigned decimal integer
- `%x` - Hexadecimal (base 16) lowercase
- `%X` - Hexadecimal (base 16) uppercase
- `%%` - Percentage sign

### Return Value
- Returns the number of characters printed
- Returns -1 on error

## 🛠️ Implementation

```c
int ft_printf(const char *format, ...);
```

### Example Usage
```c
ft_printf("Hello %s, you are %d years old", "John", 25);
ft_printf("Hex: %x, Pointer: %p", 255, ptr);
```

## 📋 Requirements

- GCC compiler
- Make
- Your libft library

## 🚀 Installation

```bash
git clone https://github.com/fsantos23/printf.git
cd ft_printf
make
```

This will create `libftprintf.a`.

## 💻 Usage

Include the header in your C file:
```c
#include "ft_printf.h"
```

Compile your program:
```bash
gcc your_program.c -L. -lftprintf
```

## ⚡ Performance

- No memory leaks
- Efficient string parsing
- Minimal buffer usage
- Handles all edge cases

## ⭐ Show your support

Give a ⭐️ if this project helped you!
