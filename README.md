# C Lox Language
Byte-code Virtual Machine Interpreter

## Lox Code Example
loop.lox
```
var a = 0;
var temp;

for (var b = 1; a < 10000; b = temp + b) {
  print a;
  temp = a;
  a = b;
}
```
## Compile and run with CMake
1. Move to source folder
2. Compile with CMake
3. Go to compiled file
4. Run in shell
```
.\clox ..\lox-scripts\loops.lox
```
