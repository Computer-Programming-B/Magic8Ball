Magic 8 Ball
============
Download the attached folder and extract the files. The folder holds artwork for a magic 8 ball.
 
For full credit, your finished program should
Provide an answer based on user input (e.g. tapping, shaking, etc.)
Store the answers in a list (called a "table" in Lua)
Use math.random() to choose one answer randomly from the table and display it
 
Have fun and be creative. Your magic 8 ball app doesn't have to work or look like anyone else's. (Students in the past have substituted different artwork to create apps like "Ask Al Gore" or "Ask Bootsy Collins.") Submit the Magic 8 Ball as a zip file through the school loop drop box.
 
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
Download Magic 8 Ball.zip
Right click on the Magic 8 Ball.zip folder and choose 7-Zip | Extract Here
Start Sublime Text 3
Choose File | New Window
Choose File | Open Folder. 
Browse to your downloads folder and open the Magic 8 Ball folder
Click on main.lua and enter the following code: display.newImage("background.png",160,240)
Run the program to confirm that you can see the picture of the 8 ball
Create another local variable to display octohedron.png
Create another local variable that uses display.newText() to display the instructions
Create a local variable that uses a table to store the possible answers
Create an Event Listener that responds to user input
Create a local function that is called by the Event Listener. The function should choose a random answer and display it
