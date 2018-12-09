# codecademy-cpp-challenge
My response to the Codecademy's C++ challenge announced on Nov 6th https://www.youtube.com/watch?v=OKQpOzEY_A4

# description of the files
initials.cpp: the original challenge, print my initials without using loops, arrays, functions...
anytext.cpp: print any text in the input string. If a character's block is not defined, it will print a blank block instead.

# how to compile and run initials.cpp
```
$ g++ initials.cpp

$ ls -al
total 136
drwxr-xr-x   8 myuser  staff   256B Dec  9 14:00 .
drwxr-xr-x  35 myuser  staff   1.1K Dec  9 13:02 ..
drwxr-xr-x  13 myuser  staff   416B Dec  9 14:02 .git
-rw-r--r--   1 myuser  staff     6B Dec  9 14:00 .gitignore
-rw-r--r--   1 myuser  staff   138B Dec  9 13:03 README.md
-rwxr-xr-x   1 myuser  staff    15K Dec  9 13:59 a.out
-rw-r--r--@  1 myuser  staff    11K Dec  9 13:59 anytext.cpp
-rw-r--r--@  1 myuser  staff   555B Dec  9 13:55 initials.cpp

$ ./a.out
FFFFF  BBBB   L
F      B   B  L
F      B   B  L
FFF    BBBB   L
F      B   B  L
F      B   B  L
F      BBBB   LLLLL
```

# instructions for anytext.cpp
Change this line with your text:
```
   string input = "Yay C++"; // here is where you input the text to be printed out
```
```
$ g++ anytext.cpp

$ ./a.out
Y   Y    A    Y   Y          CCC
 Y Y    A A    Y Y          C   C
  Y    A   A    Y           C        +      +
  Y    AAAAA    Y           C      +++++  +++++
  Y    A   A    Y           C        +      +
  Y    A   A    Y           C   C
  Y    A   A    Y            CCC
```
