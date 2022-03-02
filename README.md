# printMenu-python-
useful for when you dont want to write \n a million times

the amount of lines can extend indefiniately, and can also contain variables

text must be in a list format like so


printMenu(['title','subtitle'])


in order to add variables you must make the string into a second list like so


printMenu(['variable storage : VAR1',x])


if you want to include more than one variable simply increase VARn to as high as you need it to go as shown


printMenu(['multi variable storeage : VAR1 : VAR2',x,y])


there are currently only two arguments that this function will accept


gap : will print 40 blank lines prior to printing the list (default true)

label : will print numbers prior to each line starting after the number given (disabled by default)


label arguments output:
title
[1] start
[2] settings
[3] back
