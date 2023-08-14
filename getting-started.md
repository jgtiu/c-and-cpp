File names look like this: `myProgram.c`

Execute this command to compile code: `gcc myProgram.c`
OR execute this (I don't know what these arguments mean yet): `gcc -Wall -o hello hello.c`

Assuming that there are no errors in your code, the compiler would produce an executable program called `a.out`.

Execute this command to run executables: `./a.out`

# Setup notes, as of 2023-08-11:
Reference: https://code.visualstudio.com/docs/cpp/config-wsl

**Summary**: In this tutorial, you will configure Visual Studio Code to use the GCC C++ compiler (g++) and GDB debugger on Ubuntu in the Windows Subsystem for Linux (WSL).
- **GCC** stands for GNU Compiler Collection.
- **GDB** is the GNU debugger.
- **WSL** is a Linux environment within Windows that runs directly on the machine hardware, not in a virtual machine.

**Prerequisites** (I already did all of these before thinking of doing C/C++ development. If I remember correctly, I needed these for the Adv Web App Development class with Dr. Dennis Quan.)

Follow these guides as is:
- **Set up your Linux environment**
- **Run VS Code in WSL**
- **Add a source code file**
- **Explore IntelliSense**
- **Run helloworld.cpp**

