# Symtil - Symbolic Utility

This utility provides an enhanced method for providing functionality to your shell without relying on a particular BASH environment setup.  Unlike aliases and exported BASH functions, which require specification in a shell startup/initialization script, it provides executables in the specified PATH.  Defining functionality for Symtil allows you to make a process simpler to execute without the limitations of aliases or functions exported to BASH.

> **NOTE:** More information about the benefits of BASH aliases, functions, and scripts can be read on the [When to Use an Alias vs Script vs a New Function in Bash](https://www.baeldung.com/linux/bash-alias-vs-script-vs-new-function) article.

Conceptually working similar to the popular [BusyBox](https://busybox.net/) (file and shell utill Swiss Army Knife), when adding functionality to Symtil a symbolic link is created in the directory next to Symtil and points to it.  The added functionality and created symbolic link is named the same 
