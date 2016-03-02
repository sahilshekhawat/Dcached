A Distributed Caching system based on Memcached but build from scratch in Python.

Like Memcached it is a key-value cache where most of functionalities (like get, set, flush, add etc) are O(1). Used LRU algorithm and takes a fixed amount of memory, 1GB by default at the starting. I also have its own memory manager since syscalls like malloc or free are not optimized. Thus, it takes up memory in the beginning and manages it on its own.

It is at an very early stage. Therefore, there is nothing which we can call documentation.