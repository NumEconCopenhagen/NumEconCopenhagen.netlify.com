---
title: "Installing Python and more"
---

To follow this course you need:

1. A **Python enviroment** (we will use [Anaconda](https://www.anaconda.com))
2. A **text editor** (we will use [VSCode](https://code.visualstudio.com/), alternatives are [Sublime](https://www.sublimetext.com/), [Atom](https://atom.io/), and [PyCharm](https://www.jetbrains.com/pycharm/))
3. A **git enviroment**

# Step 1: Install Anaconda and VSCode

**Step 1a: Main**

1. Download Anaconda Python 3.6 from <https://www.anaconda.com/download/>
2. Run installer
3. When asked: Install Microsoft VSCode

**Step 1b: Extensions for Anaconda** (optional)

1. Open "Anaconda Prompt" (you might need to run as administrator)
* Run: `conda install -c conda-forge jupyter_contrib_nbextensions`
* Run: `jupyter notebook` (this opens a browser window)
* In the "Nbextensions" tab I have choosen:

    * Collapsible Headings 
    * Codefolding (*can give problems with the gutter*, add delay in settings)
    * Move selected cell
    * Split Cells Notebook
    * Table of Contents(2)

**Step 1c: Extensions for VSCode**

1. Open VSCode
2. Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>
3. Run "Extensions: Install Extensions" and install:

    * Anaconda Extensions Pack
    * Python

4. Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> again
5. Run "Python: Select Interpreter" and choose the Anaconda distribution you installed above
6. If on Windows: Run "Terminal: Select Default Shell" and choose "Command Prompt"

# Step 2: Git

1. Go to [GitHub.com](https://github.com/) and sign up
2. Download git from https://git-scm.com/
3. Run installer
4. When asked: "Visual Studio Code as Gits default editor"

**Alternative:** [GitHub Desktop](https://desktop.github.com/)