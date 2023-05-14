# Exercises

For these exercises, 
you will have to open a browser window and 
browse to this Website:
https://rodrego.it.tufts.edu/

It is a web-based program avalable on the 
[RodRego](http://sites.tufts.edu/rodrego/) Website.
The link above points to a 
version that will run in your browser.

For each of the exercises, copy the code in the indicated file, 
paste it in the code window in the Rodrego interface. 
Then initialize the values of the relevant registers and press "Play"
to see the program run. 

## Adding two numbers (nondestructive)

Try the program ```ADD_1_2_3.txt```
to test your skill at *running* register assembly programs.
The code is available in the script ```ADD_1_2_3.txt``` above
and is copied here for your convenience.

```
1  DEB 3  1  2
2  DEB 4  2  3
3  DEB 1  4  6
4  INC 3  5
5  INC 4  3
6  DEB 4  7  8
7  INC 1  6
8  DEB 2  9 11
9  INC 3 10
10 INC 4  8
11 DEB 4 12 13
12 INC 2 11
13 END
```


## Subtracting two numbers

This is the assignment question.
Can you *write* a program that correctly subtracts
the value in register 2 from the value in register 1
and places the difference in register 4?
Leave register 3 blank for now. 

