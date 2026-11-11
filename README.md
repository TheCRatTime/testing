# testing
**testing** - unit-test library

## Description
This is unit-test library that counts spent time and not breaks at test fails.

### Features
- **Small memory usage**: two **int**, one **clock_t** and **jmp_buf**
  (some **doubles** in macro)
- **C89**/**ANSI C** code standard.
- **Simple API**: see **example.c**
- **stb-style**

### Build
Needed:
- C Compiler
- CMake 3.10 and greater
- GNU Make

```bash
cmake -B build
cd build/
make
```

### Authors
TheCRatTime

### License
Project is under Apache 2.0 license.
