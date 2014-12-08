XPAL: The Parallel Architectures Library
==================================

The Parallel Architectures Library (PAL) is an open source project that 
facilitate writing programs for modern parallel architectures. 

## Why?

Most of today's low level libraries are poorly suited for modern massively
parallel architectures because they are written for single threaded processors 
with large cache hierarchies or are vendor proprietary. The future of all of 
computing is  massively parallel and requires a library that efficient, 
scalable, and completely open.

## Portable

The goal of the PAL library is to be performance and code portable across a 
number of hardware architectures, ranging from the smallest CPUs with 
limited amount of memoryto massive multicores with MBs of memory.

The low level HAL API does assume a shared physical address space.

##Independent 

PAL should conform to ANSI-C/C99/POSIX. 
 
## Fast

Speed and energy consumption (tightly related concepts) are first order
citizens in the design PAL. At times, this means error checking is thrown
out the window or that certain features of a the traditional API must be 
omitted.

## Scalable

The library is written to support different methods of parallel computing 
ranging from SIMD at the core level to massive parallelism across machines.

## Components

1.) Hardware abstraction layer for things like DMAs, interrupts timers, etc  
2.) Parallel programming support functions  
3.) Single threaded math and signal processing functions that runs inside local 
memory


Getting started (build instructions)
===============
TBD

Usage examples
==============
TBD

Contributing
=============

Want to contributed to PAL? There are instructions to get you started [here](CONTRIBUTING.md). 

Licensing
=========
PAL is licensed under the Apache License, Version 2.0. See LICENSE for full license text.

