# Pipelined-Cache-public

For full code, please contact Alex.

This program is a nice example of using low-level programming techniques and applying low-level architecture concepts (Processor design, bit-wise manipulation, working with raw assembly)

This project contains 3 main programs:

A simulated processor (my_p1s_sim.c) based on a simple, custom ISO developed by UofM called LC-2K. This processor can handle 8 instructions, including branching, adding, loading, and storing. An example "combination" program written in this language can be also be found. This processor is also "pipelined", meaning that it can process multiple stages of multiple instructions at the same time.
An assembler (assembler.c), which converts written LC-2K assembly to binary.
A configurable cache (cache.c) that can be used with this processor. This cache can make the processor even more efficient by storing reccently and commonly used results, allowing access without waiting for the processor. This cache supports modifying the block size, the number of sets, and the number of blocks per set.
