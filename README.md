# printf
printf function similar to one from standard C library
<img src="ft_printf.gif" alt="push-swap-animated" width="600"/>

Following options are supported:

|__length__| __d i__ |	__u o x X__ | __f__  |	__c__ |	__s__|	__p__|
|:--:|--|--|--|--|--|--|
|(none)	| int	| unsigned int|	double|	int |	char*|	void* |
|hh	| signed char |	unsigned char	|	| | | |
|h	| short int	|unsigned short int	|	| | | |
|l	| long int	| unsigned long int	|	| wint_t	| wchar_t*	| |
|ll |	long long int |	unsigned long long int|	| | | |
|L	| | |		long double| | | |				

|__flags__|__description__|
|:--:|--|
|-	| Left-justify within the given field width; Right justification is the default (see width sub-specifier).|
|+	| Forces to preceed the result with a plus or minus sign (+ or -) even for positive numbers. By default, only negative numbers are preceded with a - sign.|
|(space)|	If no sign is going to be written, a blank space is inserted before the value.|
|#	| Used with __o, x or X__ specifiers the value is preceeded with 0, 0x or 0X respectively for values different than zero. Used with __f__ it forces the written output to contain a decimal point even if no more digits follow. By default, if no digits follow, no decimal point is written.|
|0	| Left-pads the number with zeroes (0) instead of spaces when padding is specified (see width sub-specifier).|
