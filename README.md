

- Open main01.py. Before running it, what do you expect this program to do?
It will say Hello, then ask "What is my favorite color?". where the user will input a color
  - Now right click on the main1.py window and select “Run Python File in Terminal”. Click in the bottom panel, and answer the question. Describe what happened. The program said hello and asked for its favorite color. When a color is inputted, the program ends
  - What do you think the program did with what you typed in answer to the question? Nothing, the code ends with asking for the input


- Open main02.py. Before running it, describe how this is different than main01.py. It says color = the inputted color, and prints the color after you input it.
  - What do you think the color = input() will do? It will allow the program to know what the color written is.
  - Run the program in the terminal and answer the question. Did the program do what you expected? It did what I expected, it printed the color after I typed it.

- Open main03.py. Before running it, describe how this is different than main02.py.- It has a correct color now.
  - What is happening on lines 9–12? It allows for if the correct color, Red, is the input, it will say it is correct, and if any other color is the input it will say Sorry, Try again.
  - Why are lines 10 and 12 indented? They answer directly to if 9 and 11 are true or false.
  - Run the program and answer the question. What happens if you don’t capitalize Red? It says it is incorrect.
  - What does this tell you about "color"? You need to input it exactly as the program has it typed.

- Open main04.py. Before running it, describe how this is different than main03.py. It has Red or red being correct.
  - What problem is this trying to solve? It allows for a non-capitalized version of red to also be correct.
  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)? It is still incorrect.

- Open main05.py. What do you expect line 9 to do?- Makes your input all lower case
  - What problem is it trying to solve? Any capitalizations making the answer incorrect
  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)? It is incorrect

 - Open main06.py. How is line 9 different than in main05.py? It says both lower and strip instead of just lower
   - What would you guess .strip() is doing? takes away all spaces and other characters.
   - Run the program and answer the question. Is there another way of writing “red” that will break this logic? It corrects for spaces, but not for a hyphen or something similar to that.

 - Open main07.py. Before running this program, how do you expect this to be different than main06.py? It has a second, almost correct color.
   - What is happening on line 12? If the input is pink, it will tell you "Close!" Instead of being completely incorrect.
   - Run the program and answer the question. My prediction is what happened.

 - Open main08.py. What is the purpose of line 9? It allows you to keep guessing if you're wrong at first.
   - Why are lines 10–17 indented? They happen in the case that line 9 is true
   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)? There is an error and it doesn't repeat.
   - Make that change and run the program again. (To end any Python program, you can type ctrl-c) There is an indentation error.

 - Open main09.py. What is happening on line 13? It counts the number of inputs
   - What is the purpose of “count”? To count how many guesses there were
   - What is happening on line 22? There is no line 22, but on 21 after you guess correctly it shows how many guesses it took.
   - Run the program. What I predicted occured.
   
 - *Extra credit:* open main10.py. Add a comment to each line describing what it is doing (a comment follows a pound sign [#]).
 - *Extra credit:* open main11.py. What is happening on lines 6-11?
  
Commit your changes and push them back to the repository.
 

---

Instructions for forking this repository:
 
Log into your account on [github.com](https://github.com)

Go to the [exercise template page](https://github.com/BL-MSCH-C220-S20/E02a-Control-Structures) on GitHub

There is a button in the top right corner of the page labeled "Fork". Press that now

This will create an independent copy of this repository in your account that you can control and edit

Go to your GitHub home page, and select the new E02a-Control-Structures repository

On that page, you will see a green button labeled "Clone or download". Press that now. You will see a drop down box. Press the "Open in Desktop" button.

This should launch GitHub Desktop. It will ask you for a location (on your computer) where the repository may be cloned (downloaded). Choose a location that will be easy for you to find, and press the blue "Clone" button.

Once GitHub Desktop has cloned (downloaded) the code, it will be responsible for keeping the code on your local computer synchronized with the repository in your GitHub account. Now, open Visual Studio Code, and choose File->Open. Find the folder of the cloned repository and select Open.

In the left (File Explorer) panel, you should see a list of files that comprise this repository

First, edit the file called LICENSE. Replace year and name with the current year and your name. Save this file

Then open README.md. Feel free to remove any extraneous information, and then answer the questions posed in the file. You can add your answers after each question

When the time comes for you to run any of the python files, you can do so by clicking the green arrow in the top right corner of the window or by right-clicking on the code and selecting "Run Python File in Terminal". The results will appear at the bottom. If you don't see "Run Python File in Terminal" in the contextual menu, that is because VS Code doesn't have the Python extension installed. You can do that here: [https://marketplace.visualstudio.com/items?itemName=ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

When you are done editing the files, return to GitHub Desktop. In the left panel, you should see a list of the files that have changed

At the bottom of the leftmost area, you should see a text box labeled "Summary (required)". Add a message that describes what you have done; these messages are typically stated in the active-present tense. For example, "Updates the LICENSE, README.md, and completes the assignment." Push the blue "Commit to master" button

In the top bar of the window, you should see a button that is labeled "Push origin", push that now

Check out your page on GitHub. You should see the changes you made reflected there, Repeat steps 10 through 16 as necessary

When you are satisfied with your efforts, turn in a URL to your repository on Canvas

---
If you try to push your changes, and you receive a permission error, it is likely that you are trying to edit the BL-MSCH-C220-S20 copy of the repository rather than your own. Make sure you don't skip the step of forking your own copy and cloning that.

---

The grading criteria will be as follows:
 
[1 point] Repository contains a description of the project in README.md

1 point will be awarded for answering the questions associated with each of the files

10 points total (+2 points extra credit)
