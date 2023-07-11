# assembly
Personal notes and files while learning assembly.

## Compile and link assembly script
```bash
 nasm -f elf program.asm && ld -m elf_i386 -s -o program program.o
 ```

## Run program
```bash
./program
```
