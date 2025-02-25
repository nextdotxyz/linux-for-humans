Linux has some great built-in tools to help you learn how to use a command or check what flags are available for a command. One tool, `help`, is a built-in Bash command that provides help for other Bash commands (`echo`, `logout`, `pwd`, etc):

```bash
$ help echo
```

This will give you a description and the options you can use when you want to run `echo`. For other executable programs, it is convention to have an option called `--help` or something similar:

```bash
$ echo --help
```

Not all developers who ship out executables will conform to this standard, but it's probably your best shot to find some help on a program.
