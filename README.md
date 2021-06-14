# FT_PRINTF

The aim of this project is to recode the function printf defined in stdio.h

Biggest challenges i've found doing this project were to understand and implement width and precison on the different conversions used.

Since each different conversion has their own specification on how width and precision is handled.

Lots of time was spent reading microsoft documentation on printf and testing various outputs on the original function.

All code is written in accordance to the norminette version running at the time of project completion.

## How to use

Make will compile the libftprintf.a library which will need to be linked to a main.c file.

```
make
```

## Resources

[Microsoft printf docs](https://docs.microsoft.com/en-us/cpp/c-runtime-library/format-specification-syntax-printf-and-wprintf-functions?view=msvc-160)

man pages for printf have detailed information on how you should handle negative values.

## Contact

For any questions regarding my project email me at: Nuno_c11@hotmail.com

Or if you are a 42student my slack username is: ngregori

