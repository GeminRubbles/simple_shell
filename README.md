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
