# Task on creating a shell
- man_1_simple_shell - is the man page for the shell we are going to write.
- AUTHORS - file at the  root of your repository, listing all individuals having contributed content to the repository. 
- main.h - is the header file which contains the standared header file and prototype of o function used in the program.
- main.c - initialize the program with infinite loop by call the prompt function
- prompt.c - it use getline system call to read the input from the user and run infinite loop with fork to keep prompt going.
- special_character - It identiies if the special inputs such as if the frist input is slash,the user typed exit or env...
- string.c -it handles the strings(string length, write string,find string in directory,concatane strings....)
- cmd.c - it finds the command the user entered.
- execute.c - execute the command.