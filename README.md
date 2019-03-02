# Ways-To-Run-Python
At first the various ways your peers and friends run Python might be a litle confusing.  This is a high level artice that might clear that up.

# The 3 Main Ways

1. Text Editors
2. IDE's
3. Notebook Environment

> Note All the various ways can used for developing nearly any language, not just Python. 

Below is a section on each with a description and some commony used apps:

1. **Text Editors**
    - Notepad
    - TextEdit
    - [Notepad++](https://notepad-plus-plus.org/)
    - Vi
    - Vim
    - [Sublime Text](https://www.sublimetext.com/)
    - [BBEdit](https://www.barebones.com) (Text Wrangler)
    - [Visual Studio Code](https://code.visualstudio.com/) (Microsoft)

Text Editors themselves cannot run Python scripts because they dont have an interpreter to compile the code, but often the code is created in a Text Editor, then compiled (run) in Python.  

The simplest Text Editor is something like **Notepad** (PC) or **TextEdit** (MAC), but other more advanced editors like **Sublime Text** have auto-completion features and in-line suggestions to help with remembering syntax. They also have cool find and replace features and colour highlighting that makes things look a lot clearer.

To run the code when using Text Editors you need to save the file with the .py extension, then you need to have Python installed to run it.

Below I have created the obligatory first script called hello_world.py with the below line of code as its contents:
```
print('hello world')
```
Save to your home directory, maybe to a folder called `python`
```
# pwd
/Users/nico/python
# ls
hello_world.py
# cat hello_world.py
print('hello world')
```
To run it simply prefix the file name with `python`.  You will see the script will print `hello world` to the screen:
```
# python hello_world.py
hello world
#
```

Another way to run code is directly within the Python environment on your workstation.  You can type `python` into the command line, then type the code directly. Below I typed `print('hello world')` straight into Python.  

> This is not used much but worth pointing out.
```
# python
Python 3.7.2 (default, Feb  9 2019, 17:58:46)
[Clang 10.0.0 (clang-1000.10.44.4)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> print('hello world')
hello world
>>>
```
    
2. **IDE** (Integrated Developemnt Environment)
    - [PyCharm](https://www.jetbrains.com/pycharm/)
    - [Spyder](https://www.spyder-ide.org/)
    - [Thonny](https://thonny.org/)
    - [Atom](https://ide.atom.io/)

IDE's have all the features of the advanced Text Editors but with a compiler built in.  IDE's also have testing and debugging features that surpass Text Editors and help speed up code developemt.  Running, testing and debugging the scripts happens all in one place. 

> TIP Don't rely on auto-completion too much, learn that code :smile:

3. **Notebook Environments**
    - [Jupyter Notebook](https://jupyter.org/) (IPython)

Notebook Environments are often used when learning to develop and has many if not all of the functionality as advanced Text Editors and IDE's, but you can see your code and the compiled script right next to each other on the same screen.  You can also write comments in-line or around your work, and even use markdown to format the comments.  This is all very useful when learning.

> Its not just code noobs who use Notebook Environments, Data Scientists and other professionals use it as a compuational tool for scientific computing.

# Final Tip

Give them all a try, you'll probably learn a few things along the way :smile: :coffee:

EOF


