The `rm` ("remove") command is used to delete files and directories:

```bash
$ rm file1
```

Take caution when using `rm` – there is no magical trash can that you can fish out removed files. Once they are gone, they are gone for good, so be careful.

Fortunately, there are some safety measures put into place, so the average joe can't just remove a bunch of important files. Write-protected files will prompt you for confirmation before deleting them. If a directory is write-protected, it will also not be easily removed. 

Now, if you want to remove all files, whether they are write-protected or not, without prompting the user, you can use the `-f` ("force") option: 

```bash
$ rm -f file2
```

Adding the `-i` flag, like many of the other commands, will give you a prompt on whether you want to actually remove the files or directories:

```bash
$ rm -i file3
```

You can't just `rm` a directory by default, you'll need to add the `-r` flag ("recursive") to remove all the files and any subdirectories it may have:

```bash
$ rm -r directory1
```

You can remove a directory with the `rmdir` command:

```bash
$ rmdir directory2
```
