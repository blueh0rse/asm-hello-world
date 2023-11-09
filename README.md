# Learning

## Assembly

### Hello World

This code just displays "Hello, world!".

To assemble the program:

````bash
nasm -f elf helloworld.asm
````

To link the object file and create an executable file:

````bash
ld -m elf_i386 -s -o HelloWorld helloworld.o
````

To execute it:

````bash
$ ./HelloWorld
Hello, world!
````
