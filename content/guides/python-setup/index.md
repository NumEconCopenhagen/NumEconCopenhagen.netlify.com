---
title: "Installing Python and VSCode"
---

To follow this course you need:

1. A **Python enviroment** (we will use [Anaconda](https://www.anaconda.com))
2. A **text editor** (we will use [VSCode](https://code.visualstudio.com/), alternatives are [Sublime](https://www.sublimetext.com/), [Atom](https://atom.io/), and [PyCharm](https://www.jetbrains.com/pycharm/))
3. A **git enviroment**

A step-by-step guide is provided below.

<br>
  
# Step 1: Install Anaconda and VSCode
<br>
**Step 1a: Main**

1. Download Anaconda Python 3.7 from <https://www.anaconda.com/download/>
2. Run the installer (custom settings are fine)
3. When asked choose "Install Microsoft VSCode"

**Step 1b: Extensions for Anaconda** (optional)

*This just installs some extentions, which are nice, but are not necessary.*

1. Open the program **Terminal** (Mac) or **Anaconda Prompt** (Windows, you might need to run it as administrator^[This is done by right-clicking the program icon and choosing `Run as administrator`.])
2. Run: `conda install -c conda-forge jupyter_contrib_nbextensions`
3. Run: `jupyter notebook` (this opens a browser window)
4. In the `Nbextensions` tab we in particular recoommend:
    * Code prettify
    * Codefolding (*can give problems with the gutter*, add delay in settings)
    * Collapsible Headings     
    * Equation Auto Numbering
    * Execture Time
    * Move selected cell
    * Split Cells Notebook
    * Table of Contents(2)

**Step 1c: Extensions for VSCode**

1. Open **VSCode**
2. Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>
3. Run `Extensions: Install Extensions`
4. Search for and install the following extensions:
    * Anaconda Extensions Pack
    * Python  
5. Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> again
6. Run `Python: Select Interpreter` and choose the Anaconda distribution you installed above
7. If on Windows: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + run `Terminal: Select Default Shell` and choose `Command Prompt`

<br>

# Step 2: Install Git

1. Go to [GitHub.com](https://github.com/) and sign up
2. Download git from https://git-scm.com/
3. Run installer with all the custom settings

<br>

# Next guide

[Run Python in Jupyter Notebook](/guides/jupyter-notebook)

<br>
  
#### Notes
