```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ cat > newfile.txt
This is a new file.
This is a new file.
This is a new file.^D

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep new *.txt
This is a new file.
This is a new file.
This is a new file.

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ cat > oldfile.txt
This is a old file.
This is a old file.
This is a old file.^D

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep old *.txt
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep new *.txt
newfile.txt:This is a new file.
newfile.txt:This is a new file.
newfile.txt:This is a new file.

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep file *.txt
newfile.txt:This is a new file.
newfile.txt:This is a new file.
newfile.txt:This is a new file.
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep  "new file" *.txt
newfile.txt:This is a new file.
newfile.txt:This is a new file.
newfile.txt:This is a new file.

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep  "old file" *.txt
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep  "this is" *.txt

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep "this is" *.txt

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep "This is" *.txt
newfile.txt:This is a new file.
newfile.txt:This is a new file.
newfile.txt:This is a new file.
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.
oldfile.txt:This is a old file

```
>Ah ha - it is case sensitive

```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep -i "this is" *.txt
newfile.txt:This is a new file.
newfile.txt:This is a new file.
newfile.txt:This is a new file.
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.
oldfile.txt:This is a old file.
```
> This ignores case

```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep "error" foo.txt
error here
error on this line
error once more
```

```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep "davinci" *.txt
bar.txt:at davinci
bar.txt:davinci is awesome!
```

```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_18 $ grep Laurie Linz *.txt
grep: Linz: No such file or directory
bar.txt:Laurie Linz is awesome too!
foo.txt:Laurie Linz would never make a mistake
```
