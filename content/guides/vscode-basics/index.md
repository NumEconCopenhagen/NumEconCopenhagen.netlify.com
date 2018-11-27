---
title: "VSCode (basics)"
markup: "mmark"
---

This is a short guide on how to use **Visual Studio Code** (VSCode). 

Our recommendation is that you for larger projects write your functions and classes as modules in VSCode, and the only use Jupyter Notebooks for presenting the results.

1. **Open folder to work in**: <kbd>Ctrl</kbd>+<kbd>K</kbd>, <kbd>Ctrl</kbd>+<kbd>O</kbd>
2. **Create new file**: <kbd>Ctrl</kbd>+<kbd>N</kbd>
3. **Save new file**: <kbd>Ctrl</kbd>+<kbd>S</kbd> (write e.g. test.py)
4. **Write code**: Write the following lines of code:

 {{< highlight python "linenos=table" >}}
 message = 'hello world'
 print(message)
 {{< / highlight >}}

5. **Exectue file**: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + `Python: Run Python File in Terminal`
6. **Interactive session**: 
 i. Move cursor to the first line of code + <kbd>Shift</kbd>+<kbd>Enter</kbd> (interactive session launched)
 ii. Move cursor to the second line of code + <kbd>Shift</kbd>+<kbd>Enter</kbd> (code is executed)
 iii. In the terminal window write `print(message)` and run with <kbd>Enter</kbd>
 iv.Done? Kill the terminal by pressing the trash can icon
*Note:* You can also select multiple lines to run.
7. **Check for errors**: 
 i.    Add a third line of code:

  {{< highlight python "linenos=table" >}}
  message = 'hello world'
  print(message)      
  print(messages) 
  {{< / highlight >}}

 ii.    Save file: <kbd>Ctrl</kbd>+<kbd>S</kbd>
 iii.    Show all errors: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>M</kbd> 
 iv.    Find next error: <kbd>F8</kbd> 
8.  **Short cuts for changing view:**
  
 * New window: <kbd>Ctrl</kbd>+<kbd>N</kbd>
 * Open window: <kbd>Ctrl</kbd>+<kbd>O</kbd>
 * Close window: <kbd>Ctrl</kbd>+<kbd>F4</kbd>
 * Toggle window: <kbd>Ctrl</kbd>+<kbd>tab</kbd>
 * Locate symbol: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>O</kbd>
 * Go to symbol: <kbd>F12</kbd> (just peak <kbd>Alt</kbd>+<kbd>F12</kbd>)
 * Go to line: <kbd>Ctrl</kbd>+<kbd>G</kbd>
 * Zoom: <kbd>Ctrl</kbd>+<kbd>+</kbd> / <kbd>Ctrl</kbd>+<kbd>-</kbd>
 * Zen mode: <kbd>Ctrl</kbd>+<kbd>K</kbd>,<kbd>Ctrl</kbd>+<kbd>Z</kbd> 
  
9.  **Short cuts for smart editing:**

 * Move current line: <kbd>Alt</kbd>+<kbd>&uparrow;</kbd> / <kbd>&downarrow;</kbd>
 * Copy current line: <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>&uparrow;</kbd> / <kbd>&downarrow;</kbd>
 * Cut current line: <kbd>Ctrl</kbd>+<kbd>X</kbd>
 * Fold/unfold:

  * single block: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>´</kbd>  / <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>å</kbd>
  * all: <kbd>Ctrl</kbd>+<kbd>K</kbd>, <kbd>Ctrl</kbd>+<kbd>1</kbd> / <kbd>Ctrl</kbd>+<kbd>K</kbd>, <kbd>Ctrl</kbd>+<kbd>J</kbd>

 * Toggle commment: <kbd>Ctrl</kbd>+<kbd>'</kbd> 
 * Select multiple occurances: <kbd>Ctrl</kbd>+<kbd>D</kbd> (undo: <kbd>Ctrl</kbd>+<kbd>U</kbd>)
 * Select columns: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Alt</kbd>
    
**Change settings** <kbd>Ctrl</kbd>+<kbd>,</kbd>

**Change short cuts?** <kbd>Ctrl</kbd>+<kbd>K</kbd>, <kbd>Ctrl</kbd>+<kbd>S</kbd>
