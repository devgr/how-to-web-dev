# Terminal Basics

### Terminology
For the purposes of these lessons, all of these words are interchangeable with the word _terminal_. It's the place where you type commands into the computer.
- _Command line_
- _Command prompt_
- _Shell_

Also, the words _folder_ and _directory_ are interchangeable.

## Navigation
You can navigate around the terminal similar to how you can navigate around the Finder on Mac or the File Explorer on Windows.

### Where am I?
- Mac: Use the `pwd` command, which stands for "present working directory".
- Windows: Use the `cd` command.

### What's in this directory?
- Mac: Use the `ls` command, which stands for "list". If you want to see more details, use `ls -l`. If you want to see hidden files as well, use `ls -al`.
- Windows: Use the `dir` command.

### How do I make a new directory?
Use the `mkdir ` command followed by the name of the directory you would like to make. For example, `mkdir example-folder`

### How do I change directories?
Use the `cd ` command followed by the name of the directory that you want to go into. (`cd` stands for "change directory"). For example, if there is a directory called `example-folder` inside of your current directory, do `cd example-folder`

To go upwards to the parent directory, do `cd ..`

### What about directories that have spaces in them?
Spaces aren't very friendly in the terminal. You'll need to put the name inside of quotations. For example:  
Do `mkdir "long folder name"` then do `cd "long folder name"`. It won't work if you do `cd long folder name`.

### How do I navigate to a specific directory?
So far, we have been using _relative file paths_. That means navigating to a directory based on the one that you are currently in. But, you can use _absolute file paths_ in order to navigate to a specific directory, regardless of where you are currently. Absolute file paths start from the "root" of your drive and work their way down. On Mac, the root of the drive is `/`, and on Windows the root of the drive is usually `C:\`.
- Mac: Try `cd /Users` the `ls`. You should see the directories for each of the user accounts on your computer.
- Windows: Try `cd C:\Users` then `dir`. You should see the directories for each of the user accounts on your computer.

## Next up:
There are many many more terminal commands that we will learn. But for now, it's time to learn some Python! (TODO)
