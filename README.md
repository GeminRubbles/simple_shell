# simple_shell
# Implementation of sh in C programming language
# Overview
Simple Shell is a Holberton School pair project. The general goal of the project is to write a simple UNIX command interpreter.

# Content
Installation

Builtins

General Requirements

Target output

List of allowed functions

Compilation

Testing

Tasks

# Installation
git clone https://github.com/patrickdeyoreo/simple_shell.git
cd simple_shell
gcc *.c -o hsh

# Builtins
Command	Synopsis	Description
alias	alias [NAME[='VALUE'] ...]	Print and define command aliases
cd	cd [DIRECTORY]	Change the current working directory
env	env	Print the environment
exit	exit [STATUS]	Exit the shell
help	help [BUILTIN]	Print a help messages for built-ins
setenv	setenv VARIABLE VALUE	Set an environment variable
unsetenv	unsetenv VARIABLE	Unset an environment variable

# General Requirements
Allowed editors: vi, vim, emacs

All your files will be compiled on Ubuntu 14.04 LTS

Your C programs and functions will be compiled with gcc 4.8.4 using the flags -Wall -Werror -Wextra and -pedantic

All your files should end with a new line

A README.md file, at the root of the folder of the project is mandatory

Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl

No more than 5 functions per file

All your header files should be include guarded

Use system calls only when you need to

# Target output
Unless specified otherwise, your program must have the exact same output as sh (/bin/sh) as well as the exact same error output.
The only difference is when you print an error, the name of the program must be equivalent to your argv[0]
Example of error with sh:
