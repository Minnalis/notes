# make a compilation macro for c

at first were going to make a compile macro with "Make"

```bash
touch Makefile
```

then we edit it with vim and we include its functions

```bash
vim Makefile
```

we add the funcions

```
functionname:
	gcc -c cfile.c && gcc cfile.o -o run && ./run
```
