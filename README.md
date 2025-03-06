# Cache Simulator

Run cache simulator with LRU, RANDOM, and LRU_PREFER_CLEAN mode.

## Run the tests

```bash
$ make
$ ./cachesim <mode> <cache_size> <line_size> <associativity> < <trace_file>
(...)
```

For example:

```bash
$ ./cachesim LRU 32768 2048 4 < ./inputs/trace1
```
(...)
```
