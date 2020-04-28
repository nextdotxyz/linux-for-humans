
info> For this lesson, navigate to the **11-mv** directory.

The `mv` command is used for moving and renaming files. It is quite similar to the `cp` command in terms of flags and functionality. 

You can rename files like this:

```bash
$ mv oldfile newfile
```

Or you can actually move a file to a different directory: 

```bash
$ mv file1 Documents
```

And move more than one file:

```bash
$ mv file2 file3 somedirectory
```

You can rename directories as well:

```bash
$ mv directory1 directory2
```

Like `cp`, if you `mv` a file or directory it will overwrite anything in the same directory. So, you can use the `-i` flag to prompt you before overwriting anything:

```bash 
$ mv -i directory2 somedirectory
```

Let's say you did want to `mv` a file to overwrite the previous one. You can also make a backup of that file using the `-b` flag and it will just rename the old version with a `~`:

```bash
$ mv -b newfile Documents
```
