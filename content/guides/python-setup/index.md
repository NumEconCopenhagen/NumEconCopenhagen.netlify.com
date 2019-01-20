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

**Step 1b: JupyterLab (with extensions)**

1. Open the program **Terminal** (Mac) or **Anaconda Prompt** (Windows)
2. Paste in `conda install -c conda-forge jupyterlab nodejs ipympl` + <kbd>Enter</kbd>
3. Paste in `jupyter labextension install @jupyterlab/toc @jupyter-widgets/jupyterlab-manager jupyter-matplotlib` + <kbd>Enter</kbd>

**Step 1c: Extensions for VSCode**

1. Open **VSCode**
2. Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>
3. Paste in `Extensions: Install Extensions` + <kbd>Enter</kbd>
4. In the left panel: Search for and install the following extensions (if not already installed):
    * Anaconda Extensions Pack
    * Python  
5. Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> again
6. Paste in `Python: Select Interpreter` + <kbd>Enter</kbd> + choose the Anaconda distribution you installed above
7. If on Windows: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + paste in `Terminal: Select Default Shell` + <kbd>Enter</kbd> + choose `Command Prompt`

<br>

# Step 2: Install Git

1. Go to [GitHub.com](https://github.com/) and sign up
2. Download git from https://git-scm.com/
3. Run installer with all the custom settings
4. Open the program **Terminal** (Mac) or **Anaconda Prompt** (Windows) (close it if already open) 
5. Paste in `jupyter labextension install https://github.com/lckr/jupyterlab-variableInspector` + <kbd>Enter</kbd>


<br>

# Next guide

[Running Python in JupyterLab](/guides/jupyterlab)