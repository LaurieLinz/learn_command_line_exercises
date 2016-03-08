Do not ever run rm -rf /.  This command says to remove EVERYTHING starting at your root directory.  This removes everything on your computer including the operating system.  You will be left with a very expensive paperweight until you can put OSX back on it then you you still be said because everything you had will be gone. Just don't do it.  Just say no to rm -rf /.



```
(master) Laurie Linz
Lauries-MacBook-Pro:temp $ ls
iamcool.txt       somthing          uncool.txt
neat.txt          thefourthfile.txt
```

```
(master) Laurie Linz
Lauries-MacBook-Pro:temp $ rm uncool.txt

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ ls
iamcool.txt       neat.txt          somthing          thefourthfile.txt
```

```
(master) Laurie Linz
Lauries-MacBook-Pro:temp $ rm iamcool.txt neat.txt thefourthfile.txt

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ ls
somthing
```

```
(master) Laurie Linz
Lauries-MacBook-Pro:temp $ cp -r something newplace
cp: something: No such file or directory

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ cp -r somthing newplace
```

>opps typo, oh well

```
(master) Laurie Linz
Lauries-MacBook-Pro:temp $ rm somthing/awesome.txt

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ rmdir somthing

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ rm -rf newplace

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ ls
```

### Can you remove blah.txt?
```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_14 $ cd ..

(master) Laurie Linz
Lauries-MacBook-Pro:learn_command_line_exercises $ cd chapter_9

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_9 $ ls
README.md blah.txt  foo.txt   new       temp

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_9 $ rm blah.txt

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_9 $ ls
README.md foo.txt   new       temp
```



### Let's get rid of our development log file.
```
master) Laurie Linz
Lauries-MacBook-Pro:chapter_9 $ rmdir ../chapter_11/log/

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_9 $ ls ../chapter_11/
Readme.md temp
```

### Can you remove everything in the slash temp slash foo directory?
```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_14 $ rm -r temp/

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_14 $ ls
ReadmeChp14.md
```
