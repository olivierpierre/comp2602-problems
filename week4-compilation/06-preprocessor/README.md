Consider the program constituted of the following two source files: [preprocessor.c](./comp26020-problems/week4-compilation/06-preprocessor/preprocessor.c) and [preprocessor.h](./comp26020-problems/week4-compilation/06-preprocessor/preprocessor.h).

This program fails to compile due to missing header inclusions.
Correct these issues by writing the proper include preprocessor directives.
The expected output is:

```
./preprocessor
Please enter the amount of random number to generate:
10000000
Generated 10000000 numbers in 0.084871 seconds
```

To check the correctness of your program, use a use a [Linux distribution](https://github.com/olivierpierre/comp26020-devcontainer) with [check50 installed](exercise-set-1.html#installing-check50).
In a terminal, with the source file in the local directory, check with this command:

```shell
check50 -l --ansi-log olivierpierre/comp26020-problems/2024-2025/week4-compilation/06-preprocessor
```
