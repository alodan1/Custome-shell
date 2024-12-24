# Custom Shell Implementation 

## What the project does:
The shell replicates fundamental functionalities of standard shells, providing a streamlined environment for command execution.
  - Execute built-in commands like cd, status, and exit.
  - Run external commands with optional input and output redirection.
  - Manage foreground and background processes.
  - Handle signals like Ctrl+C (SIGINT) and Ctrl+Z (SIGTSTP) for process control.
  - Toggle foreground-only mode, where background processes are disabled.

## limitations:
  - Simple parsing of commands, does not handle complex shell scripting features (e.g., pipes | or conditional execution).

## Commands to run the project:
  1. git clone https://github.com/alodan1/Custome-shell
  2. cd Custom-shell
  3. make
  4. ./smallsh
Now you are in the shell can ran any command you want.
