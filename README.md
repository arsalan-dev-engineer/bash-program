# bash-program
This repository contains Bash scripts, practice files, notes, and documentation.

## Bash Commands and Concepts

This table summarises various Bash commands and concepts, providing a brief explanation and a simple example for each. It serves as a quick reference for understanding and using these commands effectively in your Bash scripts.

<br>

| Command/Concept         | Explanation                                     | Example                                      |
|-------------------------|-------------------------------------------------|----------------------------------------------|
| `-f`                    | Checks if the specified path is a regular file | `if [ -f "file.txt" ]; then ...`           |
| `-d`                    | Checks if the specified path is a directory    | `if [ -d "/folder/" ]; then ...`           |
| `-r`                    | Checks if the specified file is readable        | `if [ -r "file.txt" ]; then ...`           |
| `[ ... ]`               | Test command used for evaluating expressions    | `if [ -f "file.txt" ]; then ...`           |
| `grep -r "pattern"`     | Searches recursively for a pattern in files     | `grep -r "echo" ~/`                         |
| `ping`                  | Checks the connectivity to a server or IP      | `ping -c 1 www.google.com`                  |
| `printf`                | Formats and prints data to the terminal         | `printf "Hello, %s\n" "World"`              |
| `date`                  | Displays the current date and time              | `date`                                      |
| `&&`                    | Logical AND operator; executes next command if previous succeeded | `command1 && command2`                     |
| `||`                    | Logical OR operator; executes next command if previous failed | `command1 || command2`                     |
| `&>`                   | Redirects both stdout and stderr to a file      | `command &> output.log`                     |
