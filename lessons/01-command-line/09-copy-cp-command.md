
info> For this lesson, navigate to the **10-cp** directory.

Much like copy and pasting files in other operating systems, the shell gives us a simple way of making copies of files:

```bash
$ cp mycoolfile Documents/cooldocs
```

In the above command, *mycoolfile* is the file you want to copy and *Documents/cooldocs* is where you are copying the file to.

You can copy multiple files and directories, as well as use **wildcards**. A wildcard is a character that can be substituted for a pattern based selection, giving you more flexibility with searches. You can use wildcards in every command for more flexibility.

Here are some commonly used wildcards:
<ul>
<li>`*`: the wildcard of wildcards, it's used to represent all single characters or any string.</li>
<li>`?`: used to represent one character</li>
<li>`[]`: used to represent any character within the brackets</li>
</ul>

For example, the below command will copy all files with the *.jpg* extension in your current directory to the *Pictures* directory:

```bash
$ cp *.jpg Pictures
```

A useful flag to use the `-r` flag. This will recursively copy the files and directories within a directory. 

Try to do a `cp` on a directory that contains a couple of files to your *Documents* directory. Didn't work did it? Well that's because you'll need to copy over the files and directories inside as well with `-r` command.

```bash
$ cp -r Fruit Documents
```

One thing to note is if you copy a file over to a directory that has the same filename, the file will be overwritten with whatever you are copying over. This is no bueno if you have a file that you don't want to get accidentally overwritten. You can use the `-i` flag ("interactive") to prompt you before overwriting a file:

```bash
$ cp -i mycoolfile Documents/cooldocs
```
