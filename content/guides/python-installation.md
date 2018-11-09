---
title: "Installing Python and VSCode"
---

To follow this course you need:

1. a **Python enviroment** (we will use [Anaconda](https://www.anaconda.com))
2. a **text editor** (we will use [VSCode](https://code.visualstudio.com/), alternatives are [Sublime](https://www.sublimetext.com/), [Atom](https://atom.io/), and [PyCharm](https://www.jetbrains.com/pycharm/))
3. a **git enviroment**

# Step 1: Install Anaconda and VSCode

**Step 1a: Main**

1. download Anaconda Python 3.6 from <https://www.anaconda.com/download/>
2. run installer
3. when asked: install Microsoft VSCode

**Step 1b: Extensions for Anaconda** (optional)

1. open "Anaconda Prompt" (you might need to run it as administrator)
2. run: `conda install -c conda-forge jupyter_contrib_nbextensions`
3. run: `jupyter notebook` (this opens a browser window)
4. in the "Nbextensions" tab I have choosen:

    * Code prettify
    * Codefolding (*can give problems with the gutter*, add delay in settings)
    * Collapsible Headings     
    * Equation Auto Numbering
    * Execture Time
    * Move selected cell
    * Split Cells Notebook
    * Table of Contents(2)

**Step 1c: Extensions for VSCode**

1. ppen VSCode
2. press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>
3. write "Extensions: Install Extensions" + <kbd>Enter</kbd>
4. search for and install the following extensions:

    * Anaconda Extensions Pack
    * Python


5. press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> again
6. write `Python: Select Interpreter` + <kbd>Enter</kbd>, and choose the Anaconda distribution you installed above
7. if on Windows: Run "Terminal: Select Default Shell" and choose "Command Prompt"

# Step 2: Git

1. go to [GitHub.com](https://github.com/) and sign up
2. download git from https://git-scm.com/
3. run installer
4. when asked: "Visual Studio Code as Gits default editor"

**Alternative:** [GitHub Desktop](https://desktop.github.com/)
