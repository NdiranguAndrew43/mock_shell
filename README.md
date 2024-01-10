# Simple Shell Project(mock)

## Description
This is a basic UNIX command line interpreter developed as part of the ALX School Software Engineering program. The project aims to create a simple shell that can handle command execution, command lines with arguments, and basic built-in commands.

## Features
- Display a prompt and wait for user input.
- Execute commands with or without arguments.
- Handle the PATH to locate executable programs.
- Implement built-in commands such as `exit` and `env`.
- Custom `getline` function for reading user input.
- Support for logical operators `&&` and `||`.
- Builtin commands: `cd`, `setenv`, `unsetenv`.
- Handle variables like `$?` and `$$`.
- Alias command to define and list aliases.
- Handle comments with `#`.
- File input mode to read commands from a file.

## Getting Started
1. Clone the repository.
2. Compile the shell using the provided compilation command.
   ```bash
   gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

