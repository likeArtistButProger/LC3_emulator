# LC3_emulator
Simple VM for LC3 introduced by Patt and Patel.

To run any LC3 program you need to have:
Compiled version of vm.c
Obj file of program you want to run

Example: 
Visual Studio Compiler windows:
cl vm.c

or

GCC :
gcc vm.c -o vm

Now you can run your program via created exe in Command Prompt (For windows):

vm.exe pathToObjFile/file.obj
