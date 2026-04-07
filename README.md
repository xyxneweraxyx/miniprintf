# mini_printf — Minimal printf Implementation
 
A lightweight reimplementation of `printf` supporting `%d`, `%i`, `%s`, `%c`, and `%%`.
 
## Usage
 
```c
int mini_printf(const char *format, ...);
```
 
Returns the number of characters written, or `-1` on an invalid format specifier.
 
## Build
 
```sh
cd bonus && make
```
 
The binary `mini_printf` is placed at the project root.
 
## Supported specifiers
 
| Specifier | Description |
|-----------|-------------|
| `%d` / `%i` | Signed integer |
| `%s` | String |
| `%c` | Character |
| `%%` | Literal `%` |
 
## Author
 
EPITECH PROJECT, 2025 — mini_printf