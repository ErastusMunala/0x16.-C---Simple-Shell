Simple Shell project done by Erastus Munala and Simon Ng'ang'a

Description :

This is a shell written in C. It is based on the Thompson Shell.
Features:
Display a prompt and wait for the user to type a command. A command line always ends with a new line.
If an executable cannot be found, print an error message and display the prompt again.
Handle errors.
Handling the “end of file” condition (Ctrl+D)
Handling the command line with arguments
Handle the PATH
Support the exit features and the exit status
Handle the Ctrl-C to not terminate the shell
Handling the command seperator ;
Handling && and || logical operators
Handle variable replacements $? and $$
Handle the comments #
Support the history feature
Support the file input

Builtins

Our shell has support for the following built-in commands:
Command 	Definition
exit [n] 	Exit the shell, with an optional exit status, n.
env 	        Print the environment.
setenv [var][value] 	Set an environment variable and value. If the variable exists, the value will be updated.
alias[name[='value]] 	Reads aliases name
unsetenv [var] 	Remove an environment variable.
cd [dir] 	Change the directory.
help [built-in] 	Read documentation for a built-in.
