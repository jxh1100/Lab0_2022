# Lab0 - Python Introduction

This is a readme file that outlines the repo functions and installations. Every lab, project, and assignment must have a corresponding repo.

## Github

The majority of this course uses github. If you are unfamiliar with GitHub, please see [this](https://guides.github.com/activities/hello-world/) page.

GitHub Desktop makes it easy to manage repos. You may download GitHub Desktop to your local machine and pull this repo.

## Installation

Please follow the python 3.7 installation instructions [here](https://www.python.org/downloads/). If prompted, please check the box "add Python 3.7 to system path"

### Windows Users
Please be sure that your python is added to your system path. Use this [process](https://datatofish.com/add-python-to-windows-path/)

## Unix Basics

Here are basic commands to navigate UNIX and edit files

### File/Directory Manipulation
When you open a terminal window, you're placed at a command prompt:
`[cs188-ta@nova ~]$`

The prompt shows your username, the host you are logged onto, and your current location in the directory structure (your path). The tilde character is shorthand for your home directory. Note your prompt may look slightly different. To make a directory, use the mkdir command. Use cd to change to that directory:

`[cs188-ta@nova ~]$ mkdir foo`

`[cs188-ta@nova ~]$ cd foo`

`[cs188-ta@nova ~/foo]$`

Use ls to see a listing of the contents of a directory, and touch to create an empty file:

`[cs188-ta@nova ~/foo]$ ls`

`[cs188-ta@nova ~/foo]$ touch hello_world`

`[cs188-ta@nova ~/foo]$ ls`

>>hello_world

`[cs188-ta@nova ~/foo]$ cd ..`

`[cs188-ta@nova ~]$`


Some other useful Unix commands:
 - `cd` changes your common directory
 - `cp` copies a file or files
 - `rm` removes (deletes) a file
 - `mv` moves a file (i.e., cut/paste instead of copy/paste)
 - `pwd` prints your current path
 - Press "Ctrl-c" to kill a running process
 
 
 ## Python Basics
 
In this course, we will primarily use Python IDEs and Jupyter Notebooks. It is suggested to use the community edition of PyCharm as your IDE.
 
 ### Installing Packages
 
For basic python, pip is used as your package manager. Please see the user guide [here](https://pip.pypa.io/en/stable/user_guide/)
 
From your command line/prompt, install a package using the following code:

`pip3 install package_name`

package_name is replaced with whatever package you are installing.


### Installing Packages from a requirements file

Many labs and assignments will have a requirements.txt file. You can install the packages in the file using this line:

`pip3 install -r requirements.txt`

Try running the above line on your computer.

## Jupyter Notebook

Jupyter notebooks allow a mix of legible text and code, making them useful for data processing and machine-learning test beds.

Lab 0 contains a jupyter notebook. Navigate to the repos local directory on your system using `cd path/to/directory`. Then run the following line:

`jupyter notebook`

This line should open the jupyter notebook home page in your web browser. Open Lab 0 Python Basics to continue with this lab.


## Numpy and Pandas

We will be using Numpy and Pandas later on in the course. Feel free to work on the two jupyter notebooks to familiarize yourself with these two packages.

 
 
 
 
 
 
