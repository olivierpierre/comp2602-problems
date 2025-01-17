The following program is supposed to print `hi there` on the standard output and exit:
```c
#include <stdio.h>

int main(int argc, char **argv) {
    char string[8];

    string[0] = 'h';
    string[1] = 'i';
    string[2] = ' ';
    string[3] = 't';
    string[4] = 'h';
    string[5] = 'e';
    string[6] = 'r';
    string[7] = 'e';
    string[8] = '\n';

    printf("%s\n", string);

    return 0;
}
```

However, when compiled and executed it prints additional garbage values:
```
gcc string.c -o string
./string
hi there
�Fy+V
```

Modify the program so that it produces the expected output:
```
hi there
```

The string should still be created in the code in a character by character basis, i.e. solutions using `char string[] = "hi there"` will not be accepted.

To check the correctness of your program, use a use a [Linux distribution](https://github.com/olivierpierre/comp26020-devcontainer) with [check50 installed](exercise-set-1.html#installing-check50) and write your solution in a file named **`string.c`**.
In a terminal, with that file in the local directory, check with this command:

```shell
check50 -l --ansi-log olivierpierre/comp26020-problems/2024-2025/week2-c-basics/06-string
```