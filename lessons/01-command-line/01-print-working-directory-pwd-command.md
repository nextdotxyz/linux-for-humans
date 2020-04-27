Everything in Linux is a file, and every file is organized in a hierarchical directory tree. The first directory in the filesystem is aptly named the **root directory**. The root directory has many files and folders, in which you can store more files and folders, etc. Here is an example of what the directory tree looks like: 

```
|-- bin
|   |-- file1
|   |-- file2
|-- etc
|   |-- file3
|   `-- directory1
|       |-- file4
|       `-- file5
|-- home
|-- var
```

The location of these files and directories are referred to as **paths**. If you had a folder named *home* with a folder inside of it named *pete* and another folder in that folder called *Movies*, that path would look like this: 

```bash
/home/pete/Movies
```

Navigation of the filesystem, much like real life, is helpful if you know where you are and where you are going. To see where you are, you can use the `pwd` command. This command means **print working directory** and it shows you which directory you are in. Note that the path stems from the root directory.

```bash
$ pwd
```

Where are you? Where am I? Give it a try.
