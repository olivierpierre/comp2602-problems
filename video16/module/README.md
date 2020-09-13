# Video 16 Problem 5

The program [module.cpp](module.cpp) contains two classes managing pairs and
trios of integers and the multiply/addition operations that can be performed
on these. The goal of the exercise is to break down `module.cpp` into several
files:

- `Pair.h` and `Pair.cpp` managing the pair class
- `Trio.h` and `Trio.cpp` managing the trio class
- `main.cpp` containing the rest of the program

The expected output is:
```shell
./module
multiply 42 and 100: 4200
add 42 and 100: 142
multiply 10, 20 and 30: 6000
add 10, 20 and 30: 60
```

To check the correctness of your program, use CS50 [sandbox](sandbox.cs50.io)
or [IDE](ide.cs50.io). In a terminal, with all the mentioned source files in
the local directory, check with this command:
```shell
check50 -l --log olivierpierre/comp26020-problems/master/video16/module
```