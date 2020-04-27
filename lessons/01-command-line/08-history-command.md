In your shell, there is a log of all the commands that you previously entered. Using the `history` command, you can look through this log. This is quite useful when you want to find and run a command you used previously without actually typing it again.

```bash
$ history
```

If you want to run the same command you did before, just hit the *Up* arrow.

If you want to run the previous command without typing it again, use `!!`.

Another history shortcut is *Ctrl-R*. This is the reverse search command. If you hit *Ctrl-R* and you start typing parts of the command you want, it will show you matches and you can just navigate through them by hitting *Ctrl-R* again. Once you've found the command you want to use again, just hit the *Enter* key.

If your terminal is getting a little cluttered, you can do a little cleanup using the `clear` command to clear up your display:

```bash
$ clear
```

One of the most useful features in any command-line environment is **tab completion**. If you start typing the beginning of a command, file, directory, etc and hit the *Tab* key, it will autocomplete based on what it finds in the directory you are searching, as long as you don't have any other files that start with those letters. For example if you were trying to run the command `chrome`, you can type `chr` and press *Tab* and it will autocomplete `chrome`.
