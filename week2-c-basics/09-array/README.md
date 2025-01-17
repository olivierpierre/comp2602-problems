Write a program that takes up to 10 integers as command line parameters.
These parameters are converted to integer types into an array of `int` named `array`.
Then, the program sorts the array by increasing value and prints the result as follows:

```shell
./array 5 4 6 2 1 3 
1 2 3 4 5 6

./array 5 5 120
5 5 120
```

To check the correctness of your program, use a use a [Linux distribution](https://github.com/olivierpierre/comp26020-devcontainer) with [check50 installed](exercise-set-1.html#installing-check50) and write your solution in a file named **`array.c`**.
In a terminal, with that file in the local directory, check with this command:

```shell
check50 -l --ansi-log olivierpierre/comp26020-problems/2024-2025/week2-c-basics/09-array
```