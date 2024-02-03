# ft_printf

My version of `printf` in C, for 42 Roma Luiss. It handles `%c %s %p %d %i %u %x %X %%` and returns the number of characters printed, like the real one.

I then used it in minitalk and so_long.

## Build

```bash
make          # libftprintf.a
```

```c
#include "ft_printf.h"

int main(void)
{
	ft_printf("%s has %d legs, hex %x, pointer %p\n", "a spider", 8, 255, &main);
	return (0);
}
```

```bash
cc main.c libftprintf.a
```
