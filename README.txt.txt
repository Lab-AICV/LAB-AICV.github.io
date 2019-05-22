##############################################

Running on Windows

To get jemdoc running on Windows, follow the steps below (originally obtained from https://iancassidy.com/jemdoc4win.html):

Step 1: Download and install the newest version of Python 2

Step 2: Download jemdoc.py and the corresponding jemdoc.css file (both included in this folder)

Step 3: Make sure the python.exe, jemdoc.py, and jemdoc.css files are in the same folder (e.g., C:/Program Files/Python26) (if you have Python set up as a PATH variable, you dont need it in the location (if you type "python --version" into command prompt and it says Python 2._._, then you have it set up as a path variable))

Step 4: Create an input file (e.g., index.txt) using notepad or any other word processing program and make a jemdoc website

Step 5: Change the extension of your input file to index.jemdoc. Instructions for how to gain access to file extensions can be found here

Step 6: Open Command Prompt and change the directory to the location of your input file

Step 7: Run the command jemdoc.py index.jemdoc. The file index.html should appear in the same folder as index.jemdoc

#############################################

Command to compile site:

jemdoc.py [file names]

eg. With the files:
jemdoc.py
contact.jemdoc
index.jemdoc
members.jemdoc
news.jemdoc
portfolio.jemdoc
positions.jemdoc
publications.jemdoc
research.jemdoc

The command is:
jemdoc.py index contact members news portfolio positions publications research

#############################################

For future assistance:
Trevor Smith
tsmith37@uoguelph.ca/trevorsmith036@gmail.com
519-829-5125