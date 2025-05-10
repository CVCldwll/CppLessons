# Hello, World
## Programs
- because computers are really "dumb"

## The classic first program
- special characters
- importing facilities from libraries
- main function

## Compilation
- source code vs. object code
- zero tolerance for errors in code

## Linking
- puts together separate parts (modules, translation units)
- produces the executable file
- accessing declarations from libraries
- compile-time errors found by compiler
- run-time errors, logic errors found by linker (more difficult to fix)

## Programming environments
- command line
- IDE with "helpful" features 

## Drill

### VS Code
- import std; will not work; using #include<iostream>
- cl.exe compiler was not working
- MinGW seems to work with example code at https://code.visualstudio.com/docs/cpp/config-mingw

#### GCC
- I had better success with using the WSL-Debian-CLI tools
### Notes
- I cannot find 'std'
- cppreference says std::cout comes from iostream, so why does he say to "import std" 
- just use '#include <iostream>' if 'import std' will not work

or

- 'g++ -std=c++20 -fmodules-ts -x c++-system-headers iostream'
-- puts a directory structure so that "import" can happen (?)

---

## Questions
- What is the point of "import" over include?
