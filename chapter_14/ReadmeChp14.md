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
