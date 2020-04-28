# Grep only specific files

You can specify which files should be taken into account by `grep` using
`--include` switch. It supports wildcards.

```
 grep -ir --include \*.h --include \*.cpp STRING ~/path
```
