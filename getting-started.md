File names look like this: `myProgram.c`

Execute this command to compile code: `gcc myProgram.c`

Assuming that there are no errors in your code, the compiler would produce an executable program called `a.out`.

Execute this command to run executables: `./a.out`

# Setup notes, as of 2023-08-11:
Reference: https://code.visualstudio.com/docs/cpp/config-wsl

**Summary**: In this tutorial, you will configure Visual Studio Code to use the GCC C++ compiler (g++) and GDB debugger on Ubuntu in the Windows Subsystem for Linux (WSL).
- **GCC** stands for GNU Compiler Collection.
- **GDB** is the GNU debugger.
- **WSL** is a Linux environment within Windows that runs directly on the machine hardware, not in a virtual machine.

**Prerequisites**
(I already did all of these before thinking of doing C/C++ development. If I remember correctly, I needed these for the Adv Web App Development class with Dr. Dennis Quan.)
1. Install [Visual Studio Code](https://code.visualstudio.com/download).
2. Install the [WSL extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl).
3. Install [Windows Subsystem for Linux](https://learn.microsoft.com/windows/wsl/install) and then use the links on that same page to install your Linux distribution of choice.

**Set up your Linux environment**
1. Open the Bash shell for WSL. If you installed an Ubuntu distro, type "Ubuntu" in the Windows search box and then click on it in the result list.
2. 
