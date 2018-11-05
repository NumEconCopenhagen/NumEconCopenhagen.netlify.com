---
title: "VS Code (basic)"
---

## General work-flow

Write Python files (.py) files in VSCode. Write Jupyter Notebooks (.ipynb) to test your code. Debug and run long Python programs from VSCode.

1. **Open Jupyter Notebook:** Open "Anaconda Promt" + run "jupyter notebook" + locate folder
2. **Open VSCode:** Open VSCode + File + Open Folder ... <kbd>Ctrl</kbd>+<kbd>K</kbd>,<kbd>Ctrl</kbd>+<kbd>O</kbd>
3. **Find erros in VSCode:** <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>M</kbd> (note: variables beginning with _ is not counted as undefined)
4. **Run Python code VSCode:** 
    * File: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + Python: Run Python File in Terminal 
    * Line(s): <kbd>Shift</kbd>+<kbd>Enter</kbd> (interactive session launched)
    * Debug: Add breakpoint <kbd>F9</kbd> + run debugger <kbd>F5</kbd> + step with <kbd>F11</kbd> (it also catches exceptions + breakpoints can be conditional, right click on them)
5. **Git in VSCode:** (it will ask you for credentials the first time)

    * **Clone:** Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> and run "Git:Clone" with desired repo
    * **Commit:** <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>G</kbd> + write message + <kbd>Ctrl</kbd>+<kbd>Enter</kbd>
    * **Sync:** <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + Git: Sync
    * **Changes:** Click on the vertical line next to the line numbers

## Short Cuts

1. **Jupyter Notebook**: Help + Edit Short Cuts + under "restart kernel and run all cells" add "Ctrl-Q"
2. **VSCode**: <https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf>

    * Short cuts: <kbd>Ctrl</kbd>+<kbd>K</kbd>, <kbd>Ctrl</kbd>+<kbd>S</kbd>
    * New window: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>N</kbd>
    * Toggle window: <kbd>Ctrl</kbd>+<kbd>tab</kbd>
    * Toggle commment: <kbd>Ctrl</kbd>+<kbd>'</kbd>    
    * Move current line: <kbd>Alt</kbd> + <kbd>&uparrow;</kbd> / <kbd>&downarrow;</kbd>
    * Cut current line: <kbd>Ctrl</kbd>+<kbd>X</kbd>
    * Fold/unfold single: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>´</kbd>  / <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>å</kbd> (you can also collapse code between #region ... #endregion)  
    * Fold/unfold all: <kbd>Ctrl</kbd>+<kbd>K</kbd>, <kbd>Ctrl</kbd>+<kbd>1</kbd> / <kbd>Ctrl</kbd>+<kbd>K</kbd>, <kbd>Ctrl</kbd>+<kbd>J</kbd>
    * Select using selection: <kbd>Ctrl</kbd>+<kbd>D</kbd> (undo: <kbd>Ctrl</kbd>+<kbd>U</kbd>)
    * Select columns: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Alt</kbd>
    * Next error: <kbd>F8</kbd>
    * Peak defintion: <kbd>Alt</kbd> + <kbd>F12</kbd>
    * Zoom: <kbd>Ctrl</kbd>+<kbd>+</kbd> / <kbd>Ctrl</kbd>+<kbd>-</kbd>
    * Zen mode: <kbd>Ctrl</kbd>+<kbd>K</kbd> <kbd>Z</kbd>
    