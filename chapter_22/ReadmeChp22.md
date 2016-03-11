```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_22 $ export TESTING="bada bada bing"

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_22 $ echo $TESTING
bada bada bing

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_22 $ unset TESTING

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_22 $ echo $TESTING

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_22 $ env | grep TESTING
```

Alternative "english" ways of asking you to export some stuff:
Can you set the debug environment variable to true?
Can you remove the debug environment variable?
