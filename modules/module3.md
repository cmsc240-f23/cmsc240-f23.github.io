---
layout: default
permalink: module/3
---

# Module 3: Arrays, Vectors, and File I/O

* First read this page then start coding module with the GitHub classroom link below.
* Github Classroom Link: [https://classroom.github.com/a/a07rwKhv](https://classroom.github.com/a/a07rwKhv)


## Exercise 1: <a class="anchor" id="exercise_1"></a>
### Letter Counting

The code for this exercise is in the `exercise1` directory in the module3 repository. Read the description below, and then enter your code in the lettercount.cpp file where it says 
```C++
// TODO: Write your code here.
```

<div class="requirement">
When you finish and test your code, write in the README.md file how your code works.
</div>

Complete a small program to count the letters in a file. You will write a LetterCount function that takes a filename and prints to the console the number of times each letter of alphabet appears in that file. The LetterCount function should create a Vector to store the 26 numbers to be printed. For example, if the file is:

```text
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
```

then the LetterCount function will output the following:

```text
a: 29
b: 3
c: 16
d: 19
e: 38
f: 3
g: 3
h: 1
i: 42
j: 0
k: 0
l: 22
m: 17
n: 24
o: 29
p: 11
q: 5
r: 22
s: 18
t: 32
u: 29
v: 3
w: 0
x: 3
y: 0
z: 0
```

Count all letters regardless of case (so 'Ee' is two 'e').  You can use the `tolower(char)` function if needed. Ignore all non-alphbet characters. The textfile ipsum.txt is provided for testing your code.  


Here is some sample output:

```Shell
$ ./lettercount
Usage: lettercount <filename>

$ ./lettercount filedoesnotexist
Unable to open file: filedoesnotexist

$ ./lettercount ipsum.txt
a: 29
b: 3
c: 16
d: 19
e: 38
f: 3
g: 3
h: 1
i: 42
j: 0
k: 0
l: 22
m: 17
n: 24
o: 29
p: 11
q: 5
r: 22
s: 18
t: 32
u: 29
v: 3
w: 0
x: 3
y: 0
z: 0


```

<div class="requirement">

Complete the `lettercount` program.  You must read from the command line arguments to obtain a file name from the user.  You must open the file, read it, then keep the count of the letters in a vector collection.  Then iterate through that collection to print (`cout`) the letter count to the terminal.
    
</div>

---


