# Running ASM 
- Firstly asemble the asm file

``` 
yasm -f elf64 -g dwarf2 -l program.lst program.asm
```
- Then compile the created file to a runnable file

``` 
ld -o program program.o
```
- Finally run the program

```
./program
```