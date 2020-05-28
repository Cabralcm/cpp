# First C++ Program


## Install C++ on Linux

` sudo apt-get update`

` sudo apt-get upgrade`

` sudo apt-get build-essential gdb`

OR

` sudo apt-get build-essential`


## Building / Compiling C++ Code

**Compile file with generic `a.out' executable.**

- `g++ <name_of_file>.cpp`

- Output: `a.out`


**Compile file with custom name.**

- `g++ -o <output_file> <name_of_file>.cpp`

- Output: output_file


**Run compiled C++ Program:**

- `./<name of output file>`


**Aside:**
Compiling - The act of turning source code into object code

Linking - The act of combining object code with libraries into a raw executable

Building - The sequence composed of *compiling and linking*, with possibly other tasks, such as installer creation.