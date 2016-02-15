####Do more section: 

#####Make 20 more directories and remove them all.
`mkdir blue red orange yellow fuscia purple`
`mkdir -p colorado/california/texas/iowa/illinois/oregon/`
`mkdir -p apple/orange/lemon/lime/grape/dragonfruit/cherry`
`mkdir senti`
`rmdir -p apple/orange/lemon/lime/grape/dragonfruit/cherry`
`rmdir blue red orange yellow fuscia purple`
`rmdir -p colorado/california/texas/iowa/illinois/oregon/`
`rmdir senti`

####Make a single path of directories that is 10 deep and remove them one at a time just like I did above.
`mkdir -p long/straight/curly/fuzzy/snaggy/shaggy/ratty/matty/oily/greasy`
`cd long/straight/curly/fuzzy/snaggy/shaggy/ratty/matty/oily`
`rmdir greasy`
`cd ..`
`rmdir oily`
`cd ..`
`rmdir matty`
`cd ..`
`rmdir ratty`
`cd ..`
`rmdir shaggy`
`cd ..`
`rmdir snaggy/`
`cd ..`
`rmdir fuzzy/`
`cd ..`
`rmdir curly/`
`cd ..`
`rmdir straight/`
`cd ..`
`rmdir long`

no errors except typos that I omitted 

Can you remove the tmp directory? yes rmdir tmp
Let's remove the tmp directory. done

