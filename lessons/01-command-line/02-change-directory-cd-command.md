Now that you know where you are, let’s see if we can move around the filesystem a bit. Remember, we’ll need to navigate our way using paths. There are two different ways to specify a path, with **absolute** and **relative** paths. 

- Absolute path: This is the path from the root directory. The root is the head honcho. The root directory is commonly shown as a slash. Every time your path starts with **/** it means you are starting from the root directory. For example, */home/nt-user/workspace*.

- Relative path: This is the path from where you are currently in filesystem. If we were in the location */home/nt-user/workspace* and wanted to get to a directory inside *workspace* called *taxes*, we don’t have to specify the whole path from root like */home/nt-user/workspace/taxes*. We can just go to *taxes/* instead.

Now that you know how paths work, we just need something to help us change to the directory we want. The command `cd` or **change directory** does just that. 

```bash
$ cd /home/nt-user/workspace/cd-activity/Pictures
```

We've now changed our directory location to */home/nt-user/workspace/cd-activity/Pictures*.

Now from this directory we have a folder inside called *Hawaii*, we can navigate to that folder with:

```bash
$ cd Hawaii
```

Notice how we just used the name of the folder? It’s because we were already in */home/nt-user/workspace/cd-activity/Pictures*.

It can get pretty tiring navigating with absolute and relative paths all the time. Luckily, there are some shortcuts to help you out: 

- `.`  (current directory): this is the directory you are currently in.
- `..` (previous directory): takes you to the directory above your current.
- `~`  (home directory): this directory defaults to your “home directory”. Such as */home/nt-user*.
- `-`  (last directory): this will take you to the previous directory you were just in.

```bash
$ cd .
$ cd ..
$ cd ~
$ cd -
```

Give them a try!
