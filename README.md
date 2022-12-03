# volume-control
A command-line program that modifies the volume of an audio file.
> Run the 'main' executable from the command-line.
### How to compile?
> Use 'gcc' or 'clang' to compile.
```
gcc -o volume volume.c
```
```
clang -o volume volume.c
```
### How to execute?
./volume infile outfile factor
### Sample command:
```
./main input.wav output.wav 2.0
```
> **_Note_:** This is a Linux-based project and may not work natively on Windows. Run it under a WSL shell environment.
>
> Documentation: https://learn.microsoft.com/en-us/windows/wsl
