# volume-modifier
A command-line program to change the volume of an audio file.
> Run the 'main' executable from the command-line.
### How to compile?
> Make sure 'gcc' is installed.
```
gcc -o main main.c
```
### Usage:
```
./main infile outfile factor
```
### Sample command:
```
./main input.wav output.wav 2.0
```
> **_Note_:** This is a Linux-based project and may not work natively on Windows. Run it under a WSL shell environment.
>
> Documentation: https://learn.microsoft.com/en-us/windows/wsl
