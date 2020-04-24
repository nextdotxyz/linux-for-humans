With all these files we have on the system it can get a little hectic trying to find a specific one. Well there’s a command we can use for that, `find`! 

```bash
$ find ~/workspace -name banana.jpg
```

With `find` you’ll have to specify the directory you’ll be searching in and what you’re searching for, in this case we are trying to find a file by the name of *banana.jpg*. 

You can specify what type of file you are trying to find. 

```bash
$ find ~/workspace -type d -name MyFolder
```

You can see that I set the type of file I’m trying to find as `d` for directory and I’m still searching by the name of *MyFolder*. 

One cool thing to note is that `find` doesn’t stop at the directory you are searching, it will look inside any subdirectories that directory may have as well.

