# notes c

let's start making a C archive with
 
```bash
touch filename.c
```

and then edit it with vim and add the backbone 

```c
#include <stdio.h>
int main() {
	// code
	return 0;
} 
```

when you have finished,save it, and then you need to compile it with gcc into an object "filename.o"

```bash
gcc -c filename.c
```
when we have the compiled object/s, we need to create an executable file with some name we can recognise

```bash
gcc filename.o filename2.o -o "executable filename"
```

and then we run the executable with

```bash
./executable
```
