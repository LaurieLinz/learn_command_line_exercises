```
(master) Laurie Linz
Lauries-MacBook-Pro:temp $ find . -name "*.txt" -print

(master) Laurie Linz
Lauries-MacBook-Pro:temp $ cd  ..

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_17 $ find . -name "*.txt" -print | less

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_17 $ cd ..

(master) Laurie Linz
Lauries-MacBook-Pro:learn_command_line_exercises $ find . -name "*.txt" -print | less
```
I did get a long list of files returned on the last one.  


Can you show me all the files in slash temp slash foo?
```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_17 $ find . -name "*.txt" -print
./temp/foo.txt
```
What log files are in your log directory?
```
(master) Laurie Linz
 Lauries-MacBook-Pro:chapter_17 $ find log -name "*.log" -print
 log/bar.log
 log/foo.log
```
