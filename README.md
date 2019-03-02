# Ways-To-Run-Python
At first the various ways your peers and friends run Python might be confusing.  This is a high level artice to help clear up the confusion.

# The 3 Main Ways

Below are the 3 ways, a description on each, and some common apps:

1. **Text Editors**
    - Notepad
    - TextEdit
    - Notepad++
    - Vi
    - Vim
    - Sublime Text
    - BBEdit (Text Wrangler)
    - Visual Studio Code (Microsoft)

Text Editors themselves cannot run Python scripts because they dont usually have an interpreter to compile the code, but you can create the code in any text editor.  The simplest Text Editor is something like Notepad (PC) or TextEdit (MAC), but other more advanced editors like **Sublime Text** have auto-completion features and in-line suggestions to help with remembering syntax. They also have cool find and replace features and colour highlighting that makes things look a lot clearer.

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

    
2. **IDE** (Integrated Developemnt Environment)
    - PyCharm
    - Spyder
    - Thonny
    - Atom
    
3. **Notebook Environments**
    - Jupyter Notebook (IPython)
    
    
    


