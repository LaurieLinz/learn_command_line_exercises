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

Can you put "This class is fun" into bar.txt?
Can you put "Oh so much fun" into foo.txt?
```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_15 $ echo 'This class is fun' > bar.txt

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_15 $ cat bar.txt
This class is fun

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_15 $ echo 'Oh so fun' >> bar.txt

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_15 $ cat bar.txt
This class is fun
Oh so fun

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_15 $
```

The $|$ pipes the output from left to right

The $<$ writes the output from the file on the right to the one on the left and $>$ sends it to the file on the left.

$>>$ moves from left to right appending the file
