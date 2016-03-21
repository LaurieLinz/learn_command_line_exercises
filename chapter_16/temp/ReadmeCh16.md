```
(master) Laurie Linz
Lauries-MacBook-Pro:temp $ ls
ex12.txt   ex13.txt   ex14.txt   uncool.txt

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ ls *.txt
ex12.txt   ex13.txt   ex14.txt   uncool.txt

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ ls ex*.*
ex12.txt ex13.txt ex14.txt

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ ls e*
ex12.txt ex13.txt ex14.txt

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ ls *t
ex12.txt   ex13.txt   ex14.txt   uncool.txt

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ cat *.txt > bigfile.txt

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ ls
bigfile.txt ex12.txt    ex13.txt    ex14.txt    uncool.txt

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ rm *.txt

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ ls

```

As you'll learn in this chapter, * (asterisk) allows you to specify more than one file at a time.
Alternative "english" ways of using the asterisk:
 >So me anything with a __in the file name or add anything with a R in it to this commit. 

Can you output all the txt files in this directory?
> umm well I just deleted them as the exercise said, however if I had not I can search for them using `ls *.txt`

Show me the content of the text files in slash temp.
 
```
Lauries-MacBook-Pro:~ $ cd /tmp
Lauries-MacBook-Pro:tmp $ cat *.txt
Hello World
```
 

