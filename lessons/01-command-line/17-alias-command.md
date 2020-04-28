Sometimes, typing commands can get really repetitive. Or, you may need to type a long command many times. In such cases, it is best to have an `alias` you can use for the command. To create an alias for a command, you simply specify an alias name and set it to the command: 

```bash
$ alias foobar='ls -la'
```

Now, instead of typing `ls -la`, you can type `foobar` and it will execute that command. Pretty neat stuff! Keep in mind that this command won't save your alias after reboot, so you'll need to add a permanent alias in:

```bash
~/.bashrc
```

or similar files if you want to have it persist after reboot.

You can remove aliases with the `unalias` command: 

```bash
$ unalias foobar
```
