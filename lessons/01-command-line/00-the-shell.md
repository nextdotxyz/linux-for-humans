The world is your oyster, or really the shell is your oyster. What is the shell? The shell is basically a program that takes your commands from the keyboard and sends them to the operating system to perform. If you’ve ever used a GUI, you’ve probably seen terms such as **Terminal** or **Console**. These are just programs that launch a shell for you. Throughout this course, we will be learning about the wonders of the shell. 

We will use the shell program, **Bash** (**Bourne Again Shell**). Almost all Linux distributions will default to the Bash shell. There are other shells available such as ksh, zsh, tsch, but we won’t get into any of those. 

Let’s jump right in! Your shell prompt should adhere to the following format:

```bash
workspace $
```

Notice the `$` at the end of the prompt? Different shells will have different prompts; in our case, the `$` is for a normal user using Bash, Bourne or Korn shell. You don't add the prompt symbol when you type the command – just know that it's there.

Let’s start with a simple command, `echo`. The `echo` command just prints out the text arguments to the display.

```bash
$ echo Hello World
```
info> If you ever make a mistake and need cancel your last command, you can use *Ctrl + C*.
