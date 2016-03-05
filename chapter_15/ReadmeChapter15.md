`(master) Laurie Linz`
`Lauries-MacBook-Pro:chapter_15 $ cat ex12.txt ext13.txt | less`
This command flipped me to another screen with the text that I had to quit out of.

```
master) Laurie Linz
Lauries-MacBook-Pro:chapter_15 $ cat < ext13.txt
blah blah blah blah
```
Again, my exercise is quite long.  I wont use Shakespeare next time. 

```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_15 $ less < ex12.txt | cat | less
```
Same result

```
master) Laurie Linz
Lauries-MacBook-Pro:chapter_15 $ cat ext13.txt > ex15.txt

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_15 $ cat ex15.txt
blah blah blah blah
```


