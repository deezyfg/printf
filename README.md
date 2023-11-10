# 0x11. C - printf team project

This group project focuses on implementing a custom version of the printf function in C, handling various conversion specifiers and custom functionalities. Below are the tasks for this project:

## Tasks

### 0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life
Write a function that produces output according to a format.

* **Prototype:** `int _printf(const char *format, ...);`
* Returns: the number of characters printed (excluding the null byte used to end output to strings).
* Write output to stdout, the standard output stream.
* Format is a character string composed of zero or more directives. See `man 3 printf` for more detail.
* Handle the following conversion specifiers: `c`, `s`, `%`.
* You don’t have to reproduce the buffer handling of the C library printf function.
* You don’t have to handle the flag characters, field width, precision, or length modifiers.

### 1. Education is when you read the fine print. Experience is what you get if you don't
Handle the following conversion specifiers: `d`, `i`.

* You don’t have to handle the flag characters, field width, precision, or length modifiers.

### 2. With a face like mine, I do better in print
Handle the following custom conversion specifier:

* `b`: the unsigned int argument is converted to binary.

### 3. What one has not experienced, one will never understand in print
Handle the following conversion specifiers: `u`, `o`, `x`, `X`.

* You don’t have to handle the flag characters, field width, precision, or length modifiers.

### 4. Nothing in fine print is ever good news
Use a local buffer of 1024 chars to call write as little as possible.

### 5. My weakness is wearing too much leopard print
Handle the following custom conversion specifier:

* `S`: prints the string.
  * Non-printable characters (0 < ASCII value < 32 or >= 127) are printed as \x followed by the ASCII code value in hexadecimal (upper case - always 2 characters).

### 6. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print
Handle the following conversion specifier: `p`.

* You don’t have to handle the flag characters, field width, precision, or length modifiers.

### 7. The big print gives and the small print takes away
Handle the following flag characters for non-custom conversion specifiers:

* `+`
* `space`
* `#`

### 8. Sarcasm is lost in print
Handle the following length modifiers for non-custom conversion specifiers:

* `l`
* `h`
* Conversion specifiers to handle: `d`, `i`, `u`, `o`, `x`, `X`.

### 9. Print some money and give it to us for the rain forests
Handle the field width for non-custom conversion specifiers.

### 10. The negative is the equivalent of the composer's score, and the print the performance
Handle the precision for non-custom conversion specifiers.

### 11. It's depressing when you're still around and your albums are out of print
Handle the 0 flag character for non-custom conversion specifiers.

### 12. Every time that I wanted to give up, if I saw an interesting textile, print whatever, suddenly I would see a collection
Handle the - flag character for non-custom conversion specifiers.

### 13. Print is the sharpest and the strongest weapon of our party
Handle the following custom conversion specifier:

* `r`: prints the reversed string.

### 14. The flood of print has turned reading into a process of gulping rather than savoring
Handle the following custom conversion specifier:

* `R`: prints the rot13'ed string.

### 15. *
All the above options work well together.

This README provides a clear description of the tasks and the organization of your project.
