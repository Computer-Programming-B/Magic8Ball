Magic 8 Ball
============
In this project we will recreate the [magic 8 ball toy](https://www.magic8ball.org/inside-the-magic-8-ball/) using turtle graphics in Python. You may find slides 144 - 160 of the [Computer Programming B slide presentation](https://docs.google.com/presentation/d/1rICcmNbnGYsB-cV_6EatPyzcOS2sId80Jh2kayUzm4Q/edit?usp=sharing) helpful.
 
Have fun and be creative. Your magic 8 ball app doesn't have to work or look like anyone else's. (Students in the past have used different artwork to create apps like "Ask the magic olive", "Ask Al Gore" or "Ask Bootsy Collins.") 
 
The original Magic 8 Ball toy had 20 answers. You can use these answers or create your own:
+ It is certain
+ It is decidedly so
+ Without a doubt
+ Yes definitely
+ You may rely on it
+ As I see it, yes
+ Most likely
+ Outlook good
+ Yes
+ Signs point to yes
+ Reply hazy try again
+ Ask again later
+ Better not tell you now
+ Cannot predict now
+ Concentrate and ask again
+ Don't count on it
+ My reply is no
+ My sources say no
+ Outlook not so good
+ Very doubtful

Program Requirements
-------------------
For full credit, your finished program should
+ Provide an answer based on user input (e.g. clicking the mouse or typing on the keyboard)
+ Store the answers in a list
+ Use one of Python's `random` functions to choose one answer randomly from the list and display it
+ Define at least one function (e.g. a function that uses Python's turtle graphics to display a suituable picture)

Suggested steps to get started
------------------------------
1. You will need two `import` statements at the top of the program
```python
import turtle
from random import *
```
2. *Define* a function using the Python keyword `def` that draws your 8 ball or other design.
3. Call the function after its definition
4. Ask the user to enter their questions using the `textinput` function and store the question in a variable 
5. Create a list of answers, for example, `answers = ["yes","no","maybe"]`
6. Display a random answer useing the the `write()` and `randint()` function (see slides 150-152 for examples)
7. Write a `while` loop that continues to allow the user to ask questions until they indicate that they are done
8. You may find the `turtle.clearscreen()` function helpful in erasing the previous answer

Samples of Student Work
------------------------------
[Diego](Diego8Ball.gif)   
[Jason](Jason8Ball.gif)   
