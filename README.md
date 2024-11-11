# libMT19937

Implementation of the MT19937 PRNG in pure C




## Usage
Include libMT199937.h in your program. In 1 of your files where you include it add 
```c
#define LIBMT19937_IMPLEMENTATION
```

Set the Seed using 
```c
init_MT199937(get_seed()); // Or set a custom seed
```


Then start generating random numbers by using
```c
MT199937_int32
```