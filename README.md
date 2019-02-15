# How To Guide on Web Development for Beginners
_Python/JavaScript/PostreSQL track._

## Great! How do I get started?
### First, some terminology:
- You are looking at a _Git repository_ on GitHub, or _repo_ for short. It's where code lives in the cloud, and it allows for teams to collaborate on software projects.
- In the following steps, you are going to _clone_ this _repo_. That means you get a copy of it saved on your own computer.

### Cloning this repo
To get a copy of this repo on your computer, you first need to install Git. [Follow the instructions here.](https://gist.github.com/derhuerst/1b15ff4652a867391f03)

Now that you have Git installed, it's time to clone this reponsitory. Click the green "Clone or download" button on this page and copy the link it shows you. If you don't already have your terminal open, open the Terminal app (if on a Mac) or the Git Bash app (if on Windows). At your terminal, type `git clone ` and paste in the link you just coppied, then press enter. The full command will look like `git clone git@github.com:devgr/how-to-web-dev.git`. 

Next, it will be helpful to install a code editor so that you can easily view and edit these files. Download and install [Visual Studio Code](https://code.visualstudio.com/). You can also use other editors, but Visual Studio Code has lots of features and is easy to get started with.

### Opening this repo in an editor
When you cloned this repo above, a folder/directory was created on your computer with these files. Here's how to find out where on your computer those are located. At your terminal, type `cd how-to-web-dev` and hit enter, then type `pwd` (if on a Mac) or `cd` (if on Windows) and hit enter. It will tell you where you are located on your drive.

Open Visual Studio Code or the editor of your choice. Click "Open folder..." and navigate to the location that you found above, then click open. You should now see the files in this repository inside of your editor.

### Updating your repository
Later on, updates may be made to this repository on GitHub. You'll want to get those updates in your clone of the repo. To do that, you use the `git pull` command. If you still have your terminal open, you can try that command now.

If you've closed your terminal, open it again. Type `ls` (Mac) or `dir` (Windows) and hit the enter key. You should a list of files and directories, including `how-to-web-dev`. Type `cd how-to-web-dev` and hit enter. Now, you should be able to do `git pull` sucessfully.

## Next
[Navigating the Terminal](terminal/README.md)

## Outline
1. [Navigating the Terminal](terminal/README.md)
2. [Installing Python](python/installing/README.md)
3. [Python Basics: Numbers and Variables](python/numbers/README.md)
4. [Python Basics: Interactive Python](python/interactive/README.md)
5. Python Basics: Strings and I/O
6. Python Basics: Logic
7. Python Basics: Loops
8. Python Basics: Functions
9. Python Basics: Lists
10. Python Basics: Dictionaries
11. Python Basics: File I/O
12. Troubleshooting Tips and Python Exception Handling
13. Debugging Python
14. Objects in Python
15. Custom Objects - Python Class Basics

---
## Collaborating on this project
_These instructions are intended for more experienced users; don't follow these instructions if you are doing the above setup for the first time._

If you are involved in this project, send me your GitHub username and I'll add you as a collaborator on the repo so that you can push changes to it. Pull requests from the public are also welcome: Fork the repo, make your changes, then create a pull request back into this repo.
