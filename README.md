![_printf](https://imgur.com/veYYl7k.png)

This projects aims to clone the famous printf() function from the C standard library, with as much features as possible.

_printf() prints output according to a format as described below, and writes that output to stdout. The return value when successful is the length of the printed string.

## Get the function 
![Ubuntu](https://img.shields.io/badge/ubuntu-20.04-blue)
```bash
git clone git@github.com:pforciol/_printf.git
```

## Usage
```c
#include "_printf.h"
_printf(const char *format, ...);
```

## Project details
### Required libraries
- ``unistd.h``
- ``stdarg.h``
- ``stdlib.h``
- ``stdio.h``

### Examples

```c
_printf("This is a string"); // prints "This is a string"

char ch = 'a';
_printf("This is a char: %c", ch); // prints "This is a char: a"

char *str = "This is a string";
_printf("%s", str); // prints "This is a string"

int len;
len = _printf("toto"); // len is equal to strlen("toto") : 4
```

## Authors
[Pierre Forcioli](https://www.github.com/pforciol) & [Houssem Eddine Ben Khalifa](https://github.com/hosedin)
