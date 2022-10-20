Create an simple exact replica of the printf function found in the C programming language. Using Variadic functions, structs, and multiple helper functions, the program we created will be able display inputed characters, strings, integers, and decimals (base 10). Whatever format specifier you use with our _printf function, should display the same results when used by the actual printf function. This project is to show an alternative method of creating your very own simple printf function in the C programming language.

On succesfull compilation, the function should return the numbers of characters printed. The function will return (-1) if error during execution or NULL if the strigs argument takes in NULL. If the format sint _printf(const char *format, ...)


PROTOTYPE
Returns: the number of characters printed(exluding the null byte used to end the output to strings.)
Writes output to stdout.
format is a character string. see man 3 printf.pecifier is unknown, the function will print out the format specifier as a string.
