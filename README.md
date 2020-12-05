## Example
### Code:
```c
#include <stdio.h>
#include "colortext.h"

int main()
{
	printf(FORE_RED"Red "FORE_RESET BACK_RED"Red\n"BACK_RESET);
	printf(FORE_GREEN"Green "FORE_RESET BACK_GREEN"Green\n"BACK_RESET);
	printf(FORE_YELLOW"Yellow "FORE_RESET BACK_YELLOW"Yellow\n"BACK_RESET);
	printf(FORE_BLUE"Blue "FORE_RESET BACK_BLUE"Blue\n"BACK_RESET);
	printf(FORE_MAGENTA"Magenta "FORE_RESET BACK_MAGENTA"Magenta\n"BACK_RESET);
	printf(FORE_CYAN"Cyan "FORE_RESET BACK_CYAN"Cyan\n"BACK_RESET);
	printf(FORE_WHITE"White "FORE_RESET BACK_WHITE FORE_BLACK"White\n"BACK_RESET);
	printf(FORE_RESET"Reset\n");

	return 0;
}
```
### Output:
![Output](http://ibb.co.com/images/IMG_20201205_135836_559946b1014c43f35b9.jpg)