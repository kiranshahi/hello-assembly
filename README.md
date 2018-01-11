Hello, Assembly is a program written in Assemby on Ubuntu 17.10 (64 bit).


## How to run the program ?

install Netwide Assembler (NASM)
* sudo apt-get install nasm

assemble hello.asm file
* nasm -f elf64 hello.asm

link object file and create an executable file name hello
* ld -s -o hello hello.o

execute the program by typing ./hello

