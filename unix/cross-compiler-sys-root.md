# Check/Set sys-root directory for cross compiler

If compiler was built with the sys-root directory then it should be returned by
```
$ $TARGET-gcc -print-sysroot
```

Sys-root directory might be also pass to the compiler:
```
$ $TARGET-gcc --sysroot=/path/to/sysroot
```
