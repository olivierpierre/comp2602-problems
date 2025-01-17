Write a program that takes an integer as parameter and places it in a variable of type `int`.
The program then proceeds to print the value as well as the address of the variable as follows:

```shell
./pointer3 5
Variable contains 5 and is located @0x7ffcc6d1d7fc

./pointer3 93
Variable contains 93 and is located @0x7fffec3b3dfc
```

> **Printing pointers.**
> Pointer can be printed in hexadecimal and prefixed with `0x` using the
> `%p` format specifier for `printf`.

To check the correctness of your program, use a use a [Linux distribution](https://github.com/olivierpierre/comp26020-devcontainer) with [check50 installed](exercise-set-1.html#installing-check50) and write your solution in a file named `pointer3.c`.
In a terminal, with that file in the local directory, check with this command:

```shell
check50 -l --ansi-log olivierpierre/comp26020-problems/2024-2025/week3-c-pointers-stdlib/09-pointer3
```
