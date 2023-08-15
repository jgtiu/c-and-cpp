Reference: Writing, Running, and Fixing Code in C. Week 2. More Tools. Reading: Make.

Recall:

![compilation-process](images/compilation-process.png)

- Most of the time, one does not need to recompile all of the source code, if the object (`.o`) files from previous compilations are kept.
- Instead, only the file (or files) that were changed need to be recompiled, then the program needs to be linked again.
- Compiling each source file to an object file is accomplished with the `-c` option, and the various object files can then be listed on the command line to gcc in order to pass them to the linker.
- The make command reads a file called Makefile which specifies how to compile your program.
- Specifically, it names the targets which can be made, their dependencies, and the rules to make the target.