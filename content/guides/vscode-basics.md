---
title: "VS Code (basics)"
---

This is a short guide to using Visual Studio Code (VSCode).

1. **Open folder to work in**: <kbd>Ctrl</kbd>+<kbd>K</kbd>, <kbd>Ctrl</kbd>+<kbd>O</kbd>
2. **Make new file**: <kbd>Ctrl</kbd>+<kbd>N</kbd>
3. **Save new file**: <kbd>Ctrl</kbd>+<kbd>S</kbd> (write e.g. test.py)
4. **Write code**: Write the following lines of code:

      {{< highlight python "linenos=table" >}}
      message = 'hello world'
      print(message)
      {{< / highlight >}}

5. **Exectue file**: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> + "Python: Run Python File in Terminal"
6. **Interactive session**: 
   
   1. Move cursor to first line of code + <kbd>Shift</kbd>+<kbd>Enter</kbd> (interactive session launched)
   2. Move cursor to second line of code + <kbd>Shift</kbd>+<kbd>Enter</kbd>
   3. In the terminal window write "print(message)" + run with <kbd>Enter</kbd>
   4. Done? Kill terminal by pressing the trash can icon
   
   Note: You can also select multiple lines to run.

7. **Check for errors**: 
   
   1. Add the following line of code
   
      {{< highlight python "linenos=table" >}}
      print(messages)
      {{< / highlight >}}

   2. Save file, <kbd>Ctrl</kbd>+<kbd>S</kbd>
   3. Find all errors: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>M</kbd> 
   4. Find next error: <kbd>F8</kbd> 
   
8. **Short cuts for changing view:**
  
    * New window: <kbd>Ctrl</kbd+<kbd>N</kbd>
    * Open window: <kbd>Ctrl</kbd+<kbd>F4</kbd>
    * Close window: <kbd>Ctrl</kbd+<kbd>O</kbd>
    * Toggle window: <kbd>Ctrl</kbd>+<kbd>tab</kbd>
    * Locate object: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>O</kbd>
    * Go to object: <kbd>F12</kbd> (just peak <kbd>Alt</kbd>+<kbd>F12</kbd>)
    * Zoom: <kbd>Ctrl</kbd>+<kbd>+</kbd> / <kbd>Ctrl</kbd>+<kbd>-</kbd>
    * Zen mode: <kbd>Ctrl</kbd>+<kbd>K</kbd> <kbd>Z</kbd> 
  
9. **Short cuts for smart editing:**

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
