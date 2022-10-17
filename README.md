# Патрушев Никита ИС-941
# Вариант №11 - JavaScript

## Building requirements

- CMake 3.22
- ANTLR4 - 4.10.1
- GCC - 9.4.0
- Java - 11.0.15
- GNU Make - 4.2.1
- OS - Linux Ubuntu 20.04.1

#

## Build project
```./build.sh```

## Run examples
```./examples/run_fact.sh```
```./examples/run_math.sh```
```./examples/run_max.sh```
```./examples/run_nod.sh```

## Use parser
options:
  - --dump-ast
  - --dump-tokens
  - --dump-asm
  
```cd build/debug/bin```
```./js-parser [options] <filepath>```

