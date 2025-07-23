# x86 Architecture
x86 is the commonly used architecture in desktop, laptop, and servers. intel and Ryzen processors are made by this architecture.

## C into Assembly 

C is a powerful language that has ability to interact with hardware. In fact: C uses assembly to interact. C code is converted into assembly code then it is executed by assembler (software that execute the assembly code). We can convert the C code in to assembly as follows:

```
gcc -S hello.c -o hello.asm
```
This command converts the c program into assembly code.
