# Installing Python
We will be using the Python 3 language. Some operating systems come with Python 2 pre-installed. Here's the easiest way to install Python 3:

## Installation
### Mac
At the terminal, do `brew install python`. After that completes, confirm that Python is installed by doing `python3 --version`. It should output something similar to `Python 3.7.2`, although the exact number might be different.

### Windows
Go to https://www.python.org/downloads/ and download Python 3 for Windows. Open the installer once it downloads. The installer may have a checkbox like "Add Python 3 to PATH". Make sure this checkbox is checked, then continue with the installation.

Once the installation is finished, open a terminal and do `python3 --version`. It should output something similar to `Python 3.7.2`, although the exact number might be different.

## Your first Python program
Now that Python is installed, open your code editor (Visual Studio Code) and create a new file. Put the folling code in the file:
```python
print('Hello world!')
```
Save the file to a convenient location, such as in your Documents, and name it `hello.py`. All Python code files end with the `.py` extension.

In order to run the program, open a terminal and navigate to the directory where you saved the file. For example, do `cd Documents` then do `ls` to confirm that you see the `hello.py` file listed there.

Finally, do `python3 hello.py` and you should see the output: `Hello world!`. You just ran your first Python program!

## Docs
Bookmark the official docs for the Python 3 language. https://docs.python.org/3/ Although the docs are a little bit tricky to read when new to programming, they are extremely useful. Most of the examples in the following tutorials are adapted from the docs.

## Next
Using [numbers and variables in python](/python/numbers/README.md).
