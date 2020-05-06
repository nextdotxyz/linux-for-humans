How do we figure out what is available to us? Well, we can use the `ls` command to list directory contents.

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
total 28
drwxr-xr-x 2 nt-user nt-user  4 Apr 28 19:05 cat-activity
drwxr-xr-x 3 nt-user nt-user  3 Apr 28 18:36 cd-activity
drwxr-xr-x 5 nt-user nt-user 10 Apr 28 19:14 cp-activity
drwxr-xr-x 2 nt-user nt-user  3 Apr 28 19:03 file-activity
drwxr-xr-x 3 nt-user nt-user  3 Apr 28 19:27 find-activity
drwxr-xr-x 2 nt-user nt-user  3 Apr 28 19:09 less-activity
drwxr-xr-x 5 nt-user nt-user  9 Apr 28 19:20 mv-activity
drwxr-xr-x 4 nt-user nt-user  8 Apr 28 19:24 rm-activity
```

You can also combine flags, for example, `ls -la`. The order of the flags determines the order of operations. Most of the time, this doesn’t really matter so you can also do `ls -al` and it would still work.

```bash
$ ls -la
```
