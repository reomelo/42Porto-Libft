![Screenshot from 2023-11-01 16-20-45](https://github.com/reomelo/42Porto-libft/assets/73884501/6d4a00dc-fa3a-4698-99da-4d0bbe4f2ea4)

### Description of the project:
This project consists on the creation of a C header file containing recreations of already existing functions. In my case, I did the bonus alongside the mandatory, so when you run `make` both parts are executed.

### Installing and running the project:
1- Clone this repository and enter it:  

	git clone https://github.com/reomelo/42Porto-libft.git && cd 42Porto-libft

2- Run `make` and compile your program with `libft.a`:

	make && cc -Wall -Wextra -Werror main.c libft.a

### Makefile Available Targets:  
`make` or `make all` - creates libft.a      
`make clean` - wipes all object files   
`make fclean` - deletes libft.a and all object files   
`make re` - fclean  + all

___
######  At [42School](https://en.wikipedia.org/wiki/42_(school)), almost every project must be written in accordance to the [Norm](https://github.com/42School/norminette). As a result, parts of the code are not as clean, efficient or straight forward as they could be.
