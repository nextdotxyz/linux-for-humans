Now that we know how to move around the system, how do we figure out what is available to us? Right now, it’s like we are moving around in the dark. Well, we can use the `ls` command to list directory contents.

The `ls` command will list directories and files in the current directory by default. However, you can specify which path you want to list the directories of:

```bash
$ ls
$ ls /home/nt-user
```

Commands have things called flags (or arguments or options, whatever you want to call it) to add more functionality. For example, not all files in a directory will be visible using the `ls` command. Filenames that start with **.** are hidden. However, you can view them by passing the `-a` flag to it (`a` for "all"):

```bash
$ ls -a
```

There is also one more useful `ls` flag, `-l` for "long". This shows a detailed list of files in a long format. This will show you detailed information, starting from the left: file permissions, number of links, owner name, owner group, file size, timestamp of last modification, and file/directory name. 

```bash
workspace $ ls -l
total 4
drwxr-xr-x 2 nt-user nt-user 2 Apr 17 23:08 Desktop
drwxr-xr-x 2 nt-user nt-user 2 Apr 17 23:08 Documents
drwxr-xr-x 2 nt-user nt-user 2 Apr 17 23:09 Downloads
drwxr-xr-x 2 nt-user nt-user 2 Apr 17 23:09 Music
drwxr-xr-x 2 nt-user nt-user 2 Apr 17 23:09 Pictures
drwxr-xr-x 2 nt-user nt-user 2 Apr 17 23:09 Templates
drwxr-xr-x 2 nt-user nt-user 2 Apr 17 23:09 Videos
```

You can also combine flags, for example, `ls -la`. The order of the flags determines the order of operations. Most of the time, this doesn’t really matter so you can also do `ls -al` and it would still work.

```bash
$ ls -la
```
