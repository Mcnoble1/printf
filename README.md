# printf (Foundations - Low level programming & Algorithm)

> In this project, we recreated a mini-verison of the ```printf``` function found in
> the ```stdio.h``` library in the C programming language. This function allows
> us to print any argument given to the standard output or terminal and similar
> printing functions can be found in any programming language. This means we can
> print any combinations of strings, intergers, and other different data types.

### Synopsis
> This repository holds all the code necessary for our custom ```_printf```
> function to run. Our mini-version currently handles conversion specifiers:
> ```c```, ```s```, ```%```, ```d```, ```i```, ```b```, ```o```, ```x```, ```X``` and does not yet
> support field width, precision, flag characters, or length modifiers. Unique to our _printf is our ```r```
> reverse conversion and the ```R``` rot13 conversion. In essence, you can
> print any character, string, integer, or decimal number, reverse your strings, 
> transform any number to binary and octal bases, and encrypt your string with rot13 encryption. 

### Environment
* Language: C
* OS: Ubuntu 14.04 LTS
* Compiler: gcc 4.8.4
* Style guidelines: [Betty style](https://github.com/holbertonschool/Betty/wiki)

### How To Install & Compile
```
$ git clone git@github.com:selma-belhadj/printf.git
$ cd printf
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o printf
$ ./printf
```
