Magic 8 Ball
============
Download [Magic8BAll.zip](https://github.com/APCSPrinciples/Magic8Ball/blob/master/Magic%208%20Ball.zip?raw=true) and extract the files. The zip file contains a folder with the artwork for a magic 8 ball.
 
For full credit, your finished program should
+ Provide an answer based on user input (e.g. tapping, shaking, etc.)
+ Store the answers in a list (called a "table" in Lua)
+ Use `math.random()` to choose one answer randomly from the table and display it
 
Have fun and be creative. Your magic 8 ball app doesn't have to work or look like anyone else's. (Students in the past have substituted different artwork to create apps like "Ask Al Gore" or "Ask Bootsy Collins.") 
 
The original Magic 8 Ball toy had 20 answers:
● It is certain
● It is decidedly so
● Without a doubt
● Yes definitely
● You may rely on it
● As I see it, yes
● Most likely
● Outlook good
● Yes
● Signs point to yes
● Reply hazy try again
● Ask again later
● Better not tell you now
● Cannot predict now
● Concentrate and ask again
● Don't count on it
● My reply is no
● My sources say no
● Outlook not so good
● Very doubtful
 
Suggested steps to completing this assignment
---------------------------------------------
1. Download [Magic8BAll.zip](https://github.com/APCSPrinciples/Magic8Ball/blob/master/Magic%208%20Ball.zip?raw=true)
2. Right click on the Magic 8 Ball.zip folder and choose 7-Zip | Extract Here
3. Start Sublime Text 3
4. Choose *File | New Window*
5. Choose *File | Open Folder* 
6. Browse to your downloads folder and open the Magic 8 Ball folder
7. Click on `main.lua` and enter the following code: `display.newImage("background.png",160,240)`
8. Run the program to confirm that you can see the picture of the 8 ball
9. Create another local variable to display octohedron.png
10. Create another local variable that uses `display.newText()` to display the instructions
11. Create a local variable that uses a table to store the possible answers
12. Create an Event Listener that responds to user input
13. Create a local function that is called by the Event Listener. The function should choose a random answer and display it
