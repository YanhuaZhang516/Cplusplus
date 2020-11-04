# Cplusplus

### chap1: getting stared with C++
- [x] the mechanics of creating a program

### chap2: Setting Out to C++
- [x] summary

### chap3: Dealing with Data
- [x] Integer Types

Computer memory consists of units called **bits**. Short, int, long and long long can represent up to four different **integer width**.

A byte usually means an 8-bit unit of memory.
- *short*: 16 bits (2 bytes)
- *int*: at least as big as *short* (usually 4 bytes)
- *long*: at least 32 bits and at least as big as *int* 
- *long long*: at least 64 bits and at least as big as *long*


- [x] Floating-Point types

- *float*: at least 32 bits
- *double*: at least 48 bits, no smaller than *float*. 对于浮点数，double是默认类型。
- *long double*: at least as big as double, usually is 80,96,128 bits

- [x] Arithmetic Operations
- [ ] narrowing conversion, list-initialization??

转换顺序： 

long double> double> float> integer types;（低阶配合高阶）
对于 signed 和 unsigned，转向高阶的符号。


### chap4: Compound Types
- [x] arrays
- [x] strings
  - [x] getline(), get()
  - [ ] char16_t, char32_t, w_char
- [x] structures
- [x] unions
- [x] enumerations
- [x] pointers
- [x] manage dynamic memory with *new* and *delete*
  - allocate memory with *new*
  - free memory with *delete*
- [ ] dynmaic arrays
- [动态/静态数组详解](https://blog.csdn.net/chenmozhe22/article/details/106282516)

（3h20min for 130-182页）

- [ ] dynamic structures
- [ ] automatic, static, and dynamic storage
- [ ] vector and array classes


