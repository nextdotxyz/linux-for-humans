With all these files we have on the system, it can get a little hectic trying to find a specific one. Well, there's a command we can use for that – `find`!

With `find`, you'll have to specify the directory you'll be searching in and what you're searching for. In the following case we are trying to find a file by the name of *banana.jpg*:

```bash
$ find ~/workspace -name banana.jpg
```

You can also specify what type of file you are trying to find:

```bash
$ find ~/workspace -type d -name MyFolder
```

Here, we set the type of file we are trying to find as `d` ("directory") and we are still searching by the name of *MyFolder*. 

One cool thing to note is that `find` doesn't stop at the directory you are searching. It will look inside any subdirectories that directory may have as well.
