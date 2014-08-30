# Intermediate Language 

Between the compilation step and the code generation is an intermediate language. This would allow for a few important things
- A common format with which to generate code for the final output
- Common optimizations
- The ability to JIT - which will allow the same code code to work on different platforms

It may not be necessary to design a new intermediate format. There are many existing projects that have a format that d00x may be able to reuse. [GCC](http://www.gcc.org) and [LLVM](http://llvm.org) have intermediate formats that are designed to generate executable code. [.NET IL](http://en.wikipedia.org/wiki/Common_Intermediate_Language) and the [JVM bytecode](http://en.wikipedia.org/wiki/Java_bytecode) are formats designed to be compiled at runtime. [Parrot VM](http://www.parrot.org/)

This is not a particularly interesting of d00x right now. At this stage in the project, it has no differences from intermediate stages in other formats.