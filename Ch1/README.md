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
- IDE with "helpful" features  🤮
## Drill
- import std; will not work; using #include<iostream>
- cl.exe compiler was not working
- MinGW seems to work with example code at https://code.visualstudio.com/docs/cpp/config-mingw

This was a fucking disaster
where the hell is "std"?? I cannot find it--I don't think there is any such thing
cppreference says std::cout comes from iostream, so why the fuck does he say to "import std" ?!?!
typical bullshit with learning how to program
40 years of this bullshit; same thing over and over and over again; not a single correct instruction

just use #include ?
or
g++ -std=c++20 -fmodules-ts -x c++-system-headers iostream
puts a directory structure so that "import" can happen (?)
wtf is the point of "import" over include??
